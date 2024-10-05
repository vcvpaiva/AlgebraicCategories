=====Canvas pictures=====

<html>
Modular lattice <canvas id="c1" width="120" height="120"></canvas>
<script>
unit=50;
labelnode=true;
function node(x,y,t,r,nodecolor){
  nodes[t]=[];nodes[t][0]=x;nodes[t][1]=y;if(r==undefined)r=6;nodes[t][2]=r;
  if(nodecolor==undefined)nodecolor="black";nodes[t][3]=nodecolor;
}
function edge(i,j,edgecolor){
  if(edgecolor==undefined)edgecolor="black";nodecolor=nodes[i][3];
  x=nodes[i][0];y=nodes[i][1];z=nodes[j][0];w=nodes[j][1];r=nodes[i][2];
  c.strokeStyle=edgecolor;c.beginPath();c.moveTo(unit*x,c.canvas.height-unit*y);c.lineTo(unit*z,c.canvas.height-unit*w);c.stroke();
  c.strokeStyle=nodecolor;c.fillStyle="white";c.beginPath();c.arc(unit*x,c.canvas.height-unit*y,r,0,6.3,true);c.fill();if(r!=0)c.stroke();
  if(labelnode){c.fillStyle=nodecolor;c.fillText(i,unit*x-2.7,c.canvas.height-unit*y+3.5);}
}
nodes=new Array;c=document.getElementById('c1').getContext('2d');c.translate(10,-10);
node(1,2,"4");
node(0,1,"1");node(1,1,"2");node(2,1,"3");
node(1,0,"0");
edge(4,1);edge(4,2);edge(4,3);
edge(1,0);edge(2,0);edge(3,0);
edge(0,0);
</script>

<canvas id="c3" width="60" height="120"></canvas>
<script>
unit=20;nodes=new Array;c=document.getElementById('c3').getContext('2d');c.translate(10,-10);
node(1,2,"4");
node(0,1,"1");node(1,1,"2");node(2,1,"3");
node(1,0,"0");
edge(4,1);edge(4,2);edge(4,3);
edge(1,0);edge(2,0);edge(3,0);
edge(0,0);
</script>

<canvas id="c4" width="220" height="220"></canvas>
<script>
unit=20;nodes=new Array;c=document.getElementById('c4').getContext('2d');c.translate(10,-10);labelnode=false;
function chain(n,x,y){
  for(var i=0;i<n;i++) node(i+x,i+y,''+i+y);
  if(y>0) for(var i=0;i<n;i++) edge(''+i+(y-1),''+i+y);
  for(var i=0;i<n-1;i++) edge(''+i+y,''+(i+1)+y);
  edge(''+(n-1)+y,''+(n-1)+y);
}
function chain2d(m,n){
  for(var i=0;i<m;i++) chain(n,m-i-1,i);
}
chain2d(6,6)
</script>

<canvas id="c5" width="420" height="420"></canvas>
<script>
unit=20;nodes=new Array;c=document.getElementById('c5').getContext('2d');c.translate(10,-10);labelnode=false;
function chain(n,x,y){
  for(var i=0;i<n;i++) node(i+x,i+y,''+i+y);
  if(y>0) for(var i=0;i<n;i++) edge(''+i+(y-1),''+i+y);
  for(var i=0;i<n-1;i++) edge(''+i+y,''+(i+1)+y);
  edge(''+(n-1)+y,''+(n-1)+y);
}
function chain2d(m,n){
  for(var i=0;i<m;i++) chain(n,m-i-1,i);
}
chain2d(11,11)
</script>
</html>
==5-element modular lattice==
$M_3$