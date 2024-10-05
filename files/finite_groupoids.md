=====Finite nonisomorphic groupoids=====
<html>
<style>
td {padding-left:3px;padding-right:3px;}
th {background-color:#f0f0f0;font-weight:normal;padding-left:3px;padding-right:3px;}
table {border-collapse:collapse;line-height:80%;} 
</style>
Format as <select id="format" onchange="displayAlgebras(filtlist)">
<option value="table" selected>Table</option>
<option value="html">HTML</option>
<option value="text">Text</option> 
</select>
&nbsp; | &nbsp; Filter by
<b>Is subdirectly irreducible</b><input type="checkbox" name="si" id="siyes" onclick="document.getElementById('sino').checked=false;update()">yes 
<input type="checkbox" name="si" id="sino" onclick="document.getElementById('siyes').checked=false;update()">no &nbsp; 
<b>Is simple</b><input type="checkbox" name="simple" id="simpleyes" onclick="document.getElementById('simpleno').checked=false;update()">yes 
<input type="checkbox" name="simple" id="simpleno" onclick="document.getElementById('simpleyes').checked=false;update()">no &nbsp; | &nbsp;
Find algebras of size <input type="text" id="minsize" size="1" maxlength="2" value="1"> to <input type="text" id="maxsize" size="1" maxlength="2" value="3"><input type="button" value="Search" onclick="searchAlgebras()"> &nbsp; | &nbsp; Counts: <span id="counts"></span>

<div id="algebras"></div>

<script>
function algebraToString(a,k,n) {
 if (format=="html"){
  var st="<div style=\"display:inline-block;border: 1px darkgray solid;\"><sup>"+n+"</sup>"+"<b>"+classname.slice(0,1)+"</b><sub>"+a.length+","+k+"</sub><br>";
  for (var i=0; i<a.length; i++) {
    for (var j=0; j<a.length; j++) st = st+a[i][j]+(j==a.length-1?"":" &nbsp; ");
    st = st+"<br>";
  }
  st = st+"</div> &nbsp;";
 }else if (format=="table"){
  var st="<table style=\"display:inline-block;border: 1px darkgray solid;\"><tr><td colspan=\""+(a.length+1)+"\"><sup>"+n+"</sup>"+"<b>"+classname.slice(0,1)+"</b><sub>"+a.length+","+k+"</sub></td></tr><tr><th>&middot</th>";
  for (var i=0; i<a.length; i++) st += "<th>"+i+"</th>";
  st += "</tr>";
  for (var i=0; i<a.length; i++) {
    st += "<tr><th>"+i+"</th>";
    for (var j=0; j<a.length; j++)
        st = st+"<td>"+a[i][j]+"</td>";
    st = st+"</tr>";
  }
  st = st+"</table> &nbsp;";
 }else if (format=="text"){ 
  var st="{n:"+n+", name:\""+classname+"_{"+a.length+","+k+"}\", size:"+a.length+", ";
  st=st+"num:"+k+", op:{\"cdot\":[\n";
  for (var i=0; i<a.length; i++) {
    st = st+"[";
    for (var j=0; j<a.length; j++)
        st = st+a[i][j]+(j==a.length-1?"":",");
    st = st+"]"+(i==a.length-1?"]}},":",")+"\n";
  }
  st = st+"\n";
 }
 return st;
}
function checkRelation(A,rel) {//rel is a partial binary relation
    //Check that rel is transitive and compatible with the operations of A
    var op;
    var n = A.size;
    for (var x=0; x<n; x++)
	for (var y=0; y<n; y++)
            if (rel[x][y]==1 && x!=y) {
                for (var z=x+1; z<n; z++)
                    if (rel[y][z]==1)
                        if (rel[x][z]==0)
                            return false; //not transitive
		for (var r in A.op) {
		    op = A.op[r];
		    if (op.length!=null)
			if (op[0].length==null) {
			    if (rel[op[x]][op[y]]==0)
				return false;
			} else
			    for (var z=0; z<n; z++) {
				if (rel[op[x][z]][op[y][z]]==0)
				    return false;
				if (rel[op[z][x]][op[z][y]]==0)
				    return false;
			    }
		}
	    }
    return true;
}
function copyOf(arr) {
    var a = new Array(arr.length);
    for (var i=0; i<arr.length; i++) {
        a[i] = new Array(arr[i].length);
        for (var j=0; j<arr[i].length; j++) a[i][j] = arr[i][j];
    }
    return a;
}
function completeRelation(A,rel,i,j) {
    // find next i,j where rel[i][j]=2=undefined; for each val=0 or 1
    // set rel[i][j]=val, check transitivity and compatibility
    // restore and return if no completetion, 
    // else call completeRelation(rel,i,j+1)
    var ok = true;
    while (ok && i<rel.length) {
	while (j<rel.length && rel[i][j]!=2) j++;
	if (j>=rel.length) {
	    j=0; 
	    i++; 
	} else ok = false;
    }
    if (ok) congl[congl.length] = copyOf(rel);
    else for (var val=0; val<2; val++){
	    rel[i][j] = val;
	    rel[j][i] = val;
	    ok = checkRelation(A,rel);
	    if (ok) completeRelation(A,rel,i,j+1);
	    rel[i][j] = 2;
	    rel[j][i] = 2;
	}
}
function congruences(A) {
    // A is a finite algebra (JavaScript object)
    congl = [];
    var rel = new Array(A.size);
    for (var i=0; i<A.size; i++) {
        rel[i] = new Array(A.size);
	for (var j=0; j<A.size; j++) 
	    if (i!=j) rel[i][j] = 2;
	    else rel[i][j]=1;
    }
    completeRelation(A,rel,0,0);
    return congl;
}
function isSubrelation(R,S) { //assumes symmetry of relations
    for (var i=0; i<R.length; i++)
	for (var j=i+1; j<R.length; j++)
	    if (R[i][j]>S[i][j]) return false;
    return true;
}
function conLatleq(cong) { //input list of 0-1-relations
  var leq = new Array(cong.length);
  for (var i=0; i<cong.length; i++) {
      leq[i] = new Array(cong.length);
      leq[i][i] = true;
      for (var j=0; j<cong.length; j++)
	  if (i!=j) leq[i][j] = isSubrelation(cong[i],cong[j]);
  }
  return leq;
}
function leq2uppercovers(rel) {
    var n = rel.length;
    var uc = new Array(n);
    for (var i=0; i<n; i++) {
	uc[i] = [];
        for (var j=0; j<n; j++)
            if (rel[i][j] && i!=j) {
		for (var k=0; k<n && 
			 !(rel[i][k] && i!=k && rel[k][j] && k!=j); k++);
		if (k==n) uc[i][uc[i].length] = j;
	    }
    }
    return uc;
}
function congblock(co,i) {
    var block = [];
    for (var j=0; j<co.length; j++)
	if (co[i][j]==1)
	    block[block.length] = j;
    return block;
}
function cong2part(co) {
    var part = [];
    var flag = new Array(co.length);
    for (var i=0; i<co.length; i++)
        if (flag[i]==null) {
            cb = congblock(co,i);
            for (var j=0; j<cb.length; j++) flag[cb[j]]=true;
            part[part.length] = cb;
        }
    return part;
}
function conLat(A) {
    var conA = {/*name:"Con("+A.name+")",*/ rel:{}};
    var cl = congruences(A);
    conA.size = cl.length;
    conA.eltname = new Array(conA.size);
    for (var i=0; i<conA.size; i++) {
        conA.eltname[i] = cong2part(cl[i]).join(" | ");
    }
    conA.rel.uc = leq2uppercovers(conLatleq(cl));
    return conA;
}
function isSimple(A) {
    return congruences(A).length==2;
}
function isSI(A) {
    var conA = conLat(A);
    return conA.rel.uc[0].length==1;
}
///////////////////////////////////////////////////////////////////////
classname="Bin";
counts=[];
filtcounts=[];
function initializeAlgebra(n) { // finite groupoid with n elements, {0,1,...,n-1}
    var alg = new Array(n);
    for (var i=0; i<n; i++) {
	alg[i] = new Array(n);
	for (var j=0; j<n; j++)
	    alg[i][j] = n; // all elements undefined (=n)
    }
    return alg;
}
function checkAxioms(a) {
    var n,ok,x,y,z,xy,xyz;
    n = a.length;
    ok = true;
    for (x=0; ok && x<n; x++) {
        for (y=0; ok && y<n; y++) {
            xy=a[x][y];
            if (xy<n) {
//                ok = !(a[y][x]<n && xy!=a[y][x]); // check commutativity
                if (ok) {
                    for (z=0; ok && z<n; z++) {
                        xyz = a[xy][z];
                        if (xyz<n) // check associativity
                            ok = !(a[y][z]<n &&
                               a[x][a[y][z]]<n && xyz!=a[x][a[y][z]]);
		    }
		}
	    }
	}
    }
    return ok;
}
function checkPermutations(alg) {
    var i,j,ok,p,q,qi,aqi,a,equal;
    ok = true;
    var n = alg.length;
    for (p=0; ok && p<perms.length; p++) {//ok means alg <= qalg
	q = perms[p];
	qi = invperms[p];
	equal = true;
	for (i=0; equal && i<n; i++) {//equal means apij=qaij
	    for (j=0; equal && j<n; j++) {
		aqi = alg[qi[i]][qi[j]];
		a = alg[i][j];
		equal = (aqi<n && a==q[aqi]);
		if (!equal) ok = (aqi==n || a<=q[aqi]);
	    }
	}
    }
    return ok;
}
function completeAlgebra(alg,i,j) {
    // find next i,j where alg[i][j]=n=undefined; for each val=0..n-1
    // set alg[i][j]=val, check axioms and permutations
    // if ok, call completeAlg(alg,i,j+1) then restore and return
    var ok = true;
    var n = alg.length;
    while (ok && i<n) {
	while (j<n && alg[i][j]<n) j++;
	if (j>=n) {
	    j = 0; 
	    i++;
	} else ok = false;
    }
    if (ok) {
        counts[alg.length-1]++;
        alglist[alglist.length] = {size:alg.length,op:{cdot:copyOf(alg)},num:counts[alg.length-1]};
    } else for (var val=0; val<n; val++) {
	alg[i][j] = val;
	ok = true;//checkAxioms(alg);
	if (ok) ok = checkPermutations(alg);
	if (ok) completeAlgebra(alg,i,j+1);
        alg[i][j] = n;
    }
}
function nextPermutation(p) {
    var q=[];
    for (var j=p.length-2; j>=0 && p[j]>p[j+1]; j--);
    if (j<0) return [];
    for (var k=0; k<j; k++) q[k]=p[k];
    for (var k=p.length-1; p[j]>p[k]; k--);
    q[j]=p[k];
    for (var i=p.length-1; i>j; i--) q[i]=p[j+p.length-i];
    q[j+p.length-k]=p[j];
    return q;
}
function permutations(m,n) { // return list of permutations of {m,...,n}
    var perms = [];
    perms[0]=[];
    for (var i=0; i<=n-m; i++) perms[0][i]=m+i;
    for (var i=0; perms[i].length>0; i++) {
        perms[i+1]=nextPermutation(perms[i]);
    }
    perms.length=perms.length-1;
    return perms;
}
function inversePermutation(p) {
    var q=[];
    for (var i=0; i<p.length; i++)
	q[p[i]]=i;
    return q;
}
function findAlgebras(size) {
    counts[size-1]=0;
    perms = permutations(0,size-1);
    invperms = [];
    for (var i=0; i<perms.length; i++) invperms[i]=inversePermutation(perms[i]);
    alg = initializeAlgebra(size);
    completeAlgebra(alg,0,0);
}
function findAlgebrasRange(minsize,maxsize) {
    alglist = [];
    for (var i=minsize; i<=maxsize; i++)
        findAlgebras(i);
}
function update(){
  findAlgebrasRange(eval(document.getElementById('minsize').value), eval(document.getElementById('maxsize').value));
}
function filterAlgebras(As){
    var Bs = [];
    for (var i=0; i<As[As.length-1].size; i++) filtcounts[i] = 0;
    simpleyes = document.getElementById("simpleyes").checked;
    simpleno = document.getElementById("simpleno").checked;
    siyes = document.getElementById("siyes").checked;
    sino = document.getElementById("sino").checked;
    for (var i=0; i<As.length; i++) {
        var add = (!simpleyes||!simpleno) && (!siyes||!sino);
        if (add && (simpleyes||simpleno)) {
            var simple = isSimple(As[i]);
            add = simpleyes && simple || simpleno && !simple;
        }
        if (add && (siyes||sino)) {
            var si = isSI(As[i]);
            add = siyes && si || sino && !si;
        }
        if (add) {
            Bs[Bs.length] = As[i];
            filtcounts[As[i].size-1]++;
        }
    }
    filtlist = Bs;
    displayAlgebras(Bs);
}
function displayAlgebras(As){
    format = document.getElementById("format").value;
    algstr=(format=="text"?classname+"=[\n":"");
    for (var i=0; i<As.length; i++)
        algstr += algebraToString(As[i].op.cdot,As[i].num,i);
    document.getElementById("algebras").innerHTML=(format=="text"?"<textarea rows=\"35\">"+algstr.slice(0,algstr.length-3)+"];\n</textarea>":algstr);
    document.getElementById("counts").innerHTML="<a href=\"http://www.research.att.com/~njas/sequences/?q="+filtcounts.join(",+")+"&sort=0&fmt=0&language=english&go=Search\"><u><b>"+filtcounts.join(", ")+"</b></u></a>";
}
function searchAlgebras(){
    findAlgebrasRange(eval(document.getElementById('minsize').value), eval(document.getElementById('maxsize').value));
    filterAlgebras(alglist);
}
function update(){
    filterAlgebras(alglist);
}
searchAlgebras();
</script>
</html>