=====BCK-meet-semilattices=====

Abbreviation: **BCKJMlat**

====Definition====
A \emph{BCK-meet-semilattice} is a structure $\mathbf{A}=\langle A,\wedge,\rightarrow,1\rangle$ of type $\langle 2,2,0\rangle$ such that

(1):  $(x\rightarrow y)\rightarrow
((y\rightarrow z)\rightarrow (x\rightarrow z)) = 1$

(2):  $1\rightarrow x = x$

(3):  $x\rightarrow 1 = 1$

(4):  $(x\wedge y)\rightarrow y = 1$

(5):  $x\wedge((x\rightarrow y)\rightarrow y) = x$

$\wedge$ is idempotent:  $x\wedge x = x$

$\wedge$ is commutative:  $x\wedge y = y\wedge x$

$\wedge$ is associative:  $(x\wedge y)\wedge z = x\wedge (y\wedge z)$

Remark: 
$x\le y \iff x\rightarrow y=1$ is a partial order, with $1$ as greatest element, and $\wedge$ is a meet in this partial order. [(Idziak1984)]

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be BCK-meet-semilattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\wedge y)=h(x)\wedge h(y)$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$ and $h(1)=1$.

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  | |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  | |
^[[Locally finite]]  | |
^[[Residual size]]  | |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence regular]]  | |
^[[Congruence uniform]]  | |
^[[Congruence extension property]]  | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
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
[[BCK-lattices]] 

====Superclasses====
[[BCK-algebras]] 


====References====

[(Idziak1984>
Pawel M. Idziak, \emph{Lattice operation in BCK-algebras},
Math. Japon., \textbf{29}, 1984, 839--846 [[MRreview]]
)]