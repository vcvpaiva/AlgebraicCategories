=====BCK-lattices=====

Abbreviation: **BCKlat**
====Definition====
A \emph{BCK-lattice} is a structure $\mathbf{A}=\langle A,\vee,\wedge,\rightarrow,1\rangle$ of type $\langle 2,2,2,0\rangle$ such that

$\langle A,\vee,\rightarrow,1\rangle$ is a [[BCK-join-semilattice]]

$\langle A,\wedge,\rightarrow,1\rangle$ is a [[BCK-meet-semilattice]]

Remark: 
$x\le y \iff x\rightarrow y=1$ is a partial order, with $1$ as greatest element, and $\vee$, $\wedge$ are a join and meet for this order. [(Idziak1984)]

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be BCK-lattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$ and $h(1)=1$.

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
^[[Congruence n-permutable]]  |yes $n=2$ |
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
[[Heyting algebras]] 

====Superclasses====
[[BCK-join-semilattices]] 

[[BCK-meet-semilattices]] 


====References====

[(Idziak1984>
Pawel M. Idziak, \emph{Lattice operation in BCK-algebras},
Math. Japon., \textbf{29}, 1984, 839--846 [[MRreview]]
)]