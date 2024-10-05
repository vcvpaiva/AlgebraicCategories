=====Boolean modules over a relation algebra=====

Abbreviation: **BRMod**
====Definition====
A \emph{Boolean module over a [[relation algebra]]} $\mathbf{R}$ is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,f_r\ (r\in R)\rangle$ such that

$\langle A,\vee,0,\wedge,1,\neg\rangle$ is a [[Boolean algebra]]

$f_r$ is \emph{join-preserving}: $f_r(x\vee y)=f_r(x)\vee f_r(y)$

$f_{r\vee s}(x)=f_r(x)\vee f_s(x)$

$f_r(f_s(x))=f_{r\circ s}(x)$

$f_{1'}$ is the identity map:  $f_{1'}(x)=x$

$f_0(x)=0$

$f_{r^\smile}(\neg (f_r(x)))\le \neg x$

Remark: Assuming that $f_r$ is order-preserving, the last identity is equivalent to the condition that $f_{r^\smile}$ and $f_r$ are conjugate operators. 
It follows that $f_r$ is \emph{normal}: $f_r(0)=0$.

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Boolean modules over a realtion algebra. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a Boolean homomorphism and preserves all $f_r$:

$h(f_r(x))=f_r(h(x))$

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
f(2)= &\\
f(3)= &\\
f(4)= &\\
f(5)= &\\
f(6)= &\\
\end{array}$

====Subclasses====
[[One-element algebras]] 

====Superclasses====
[[Boolean algebras with operators]] 


====References====

[(Ln19xx>
)]






