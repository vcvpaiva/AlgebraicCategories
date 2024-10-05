=====Modular lattices=====

Abbreviation: **MLat**

====Definition====
A \emph{modular lattice} is a [[lattice]] $\mathbf{L}=\langle L, \vee, \wedge\rangle$ that satisfies the

\emph{modular identity}:  $((x\wedge z) \vee y) \wedge z = (x\wedge z) \vee (y\wedge z)$

====Definition====
A \emph{modular lattice} is a [[lattice]] $\mathbf{L}=\langle L, \vee, \wedge\rangle$ that satisfies the

\emph{modular law}: $x\le z\Longrightarrow (x\vee y) \wedge z\le x\vee (y\wedge z)$

====Definition====
A \emph{modular lattice} is a lattice $\mathbf{L}=\langle L,\vee,\wedge\rangle $ such that $\mathbf{L}$ has no sublattice isomorphic
to the pentagon $\mathbf{N}_{5}$ <html><canvas id="c1" width="60" height="60"></canvas>
<script>
unit=20;
labelnodes=false;
function node(x,y,t,r,nodecolor){
  nodes[t]=[];nodes[t][0]=x;nodes[t][1]=y;if(r==undefined)r=(labelnodes?6:3);nodes[t][2]=r;
  if(nodecolor==undefined)nodecolor="black";nodes[t][3]=nodecolor;
}
function edge(i,j,edgecolor){
  if(edgecolor==undefined)edgecolor="black";nodecolor=nodes[i][3];
  x=nodes[i][0];y=nodes[i][1];z=nodes[j][0];w=nodes[j][1];r=nodes[i][2];
  c.strokeStyle=edgecolor;c.beginPath();c.moveTo(unit*x,c.canvas.height-unit*y);c.lineTo(unit*z,c.canvas.height-unit*w);c.stroke();
  c.strokeStyle=nodecolor;c.fillStyle="white";c.beginPath();c.arc(unit*x,c.canvas.height-unit*y,r,0,6.3,true);c.fill();if(r!=0)c.stroke();
  if(labelnodes){c.fillStyle=nodecolor;c.fillText(i,unit*x-2.7,c.canvas.height-unit*y+3.5);}
}
nodes=new Array;c=document.getElementById('c1').getContext('2d');c.translate(10,-4);
node(1,2,"4");
node(0,0.66,"1");node(0,1.33,"2");node(2,1,"3");
node(1,0,"0");
edge(4,2);edge(4,3);
edge(2,1);
edge(1,0);edge(3,0);
edge(0,0);
</script>
</html>

==Morphisms==
Let $\mathbf{L}$ and $\mathbf{M}$ be modular lattices. 
A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$

====Examples====
Example 1: $M_3$ <html><canvas id="c2" width="60" height="60"></canvas>
<script>
nodes=new Array;c=document.getElementById('c2').getContext('2d');c.translate(10,-4);
node(1,2,"4");
node(0,1,"1");node(1,1,"2");node(2,1,"3");
node(1,0,"0");
edge(4,1);edge(4,2);edge(4,3);
edge(1,0);edge(2,0);edge(3,0);
edge(0,0);
</script></html>
is the smallest nondistributive modular lattice. By a result of [(Dedekind1900)]
this lattice occurs as a sublattice of every nondistributive
modular lattice.


====Basic results====

====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |undecidable [(Freese1980)] [(Herrmann1983)] |
^[[Quasiequational theory]]  |undecidable [(Lipshitz1974)] |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |no |
^[[Congruence regular]]  |no |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  |no |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]  |no |
^[[Amalgamation property]]  |no |
^[[Strong amalgamation property]]  |no |
^[[Epimorphisms are surjective]]  |no |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &4\\
f(6)= &8\\
f(7)= &16\\
f(8)= &34\\
f(9)= &72\\
f(10)= &157\\
f(11)= &343\\
f(12)= &766\\
f(13)= &1718\\
f(14)= &3899\\
f(15)= &8898\\
f(16)= &20475\\
f(17)= &47321\\
f(18)= &110024\\
f(19)= &256791\\
f(20)= &601991\\
f(21)= &1415768\\
f(22)= &3340847\\
f(23)= &7904700\\
f(24)= &18752942\\
f(25)= &\\
f(26)= &\\
\end{array}$[(Peter Jipsen, Nathan Lawless, \emph{Generating all finite modular lattices of a given size}, 
Algebra Universalis, \textbf{74}, 2015, 253--264)]


====Subclasses====
[[Distributive lattices]] 

[[Complete modular lattices]] 

====Superclasses====
[[Semimodular lattices]] 

[[Geometric lattices]] 


====References====

[(Dedekind1900>
Richard Dedekind, \emph{\"Uber die von drei Moduln erzeugte Dualgruppe},
Math. Ann., \textbf{53}, 1900, 371--403)]

[(Freese1980>
Ralph Freese, \emph{Free modular lattices},
Trans. Amer. Math. Soc., \textbf{261}, 1980, 81--91)]

[(Herrmann1983>
Christian Herrmann, \emph{On the word problem for the modular lattice with four free generators},
Math. Ann., \textbf{265}, 1983, 513--527)]

[(Lipshitz1974>
L. Lipshitz, \emph{The undecidability of the word problems for projective geometries and modular lattices},
Trans. Amer. Math. Soc., \textbf{193}, 1974, 171--180)]
