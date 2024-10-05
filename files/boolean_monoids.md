=====Boolean monoids=====

Abbreviation: **BMon**
====Definition====
A \emph{Boolean monoid} is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,\cdot,e\rangle$ such that


$\langle A,\vee,0,
\wedge,1,\neg\rangle $ is a [[Boolean algebra]]


$\langle A,\cdot,e\rangle $ is a [[monoids]]


$\cdot$ is \emph{join-preserving} in each argument:  
$(x\vee y)\cdot z=(x\cdot z)\vee (y\cdot z) \mbox{ and } x\cdot (y\vee z)=(x\cdot y)\vee (x\cdot z)$


$\cdot$ is \emph{normal} in each argument:  $0\cdot x=0 \mbox{ and } x\cdot 0=0$


Remark: 

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Boolean monoids. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a Boolean homomorphism and preserves $\cdot$, $e$:

$h(x\cdot y)=h(x)\cdot h(y) \mbox{ and } h(e)=e$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  | |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  | |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence regular]]  |yes |
^[[Congruence uniform]]  |yes |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]  |no |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &0\\
f(4)= &9\\
f(5)= &0\\
f(6)= &0\\
f(7)= &0\\
f(8)= &258\\
\end{array}$

====Subclasses====
[[Sequential algebras]] 

====Superclasses====
[[Boolean algebras with operators]] 


====References====

[(Ln19xx>
)]