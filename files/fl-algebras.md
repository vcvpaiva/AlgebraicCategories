=====FL-algebras=====

Abbreviation: **FL**
====Definition====
A \emph{full Lambek algebra}, or \emph{FL-algebra}, is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \backslash, /, 0\rangle$ 
of type $\langle 2,0,2,0,2,1,2,2\rangle$ such that

$\langle A, \vee, \wedge, \cdot, 1, \backslash, /\rangle$ is a 
[[residuated lattice]] and

$0$ is an additional constant (can denote any element).

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be FL-algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash y)=h(x)\backslash
h(y)$, $h(x/y)=h(x)/h(y)$, $h(1)=1$, $h(0)=0$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable [(OK1985)] |
^[[Quasiequational theory]]  |undecidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, n=2 |
^[[Congruence regular]]  |no |
^[[Congruence e-regular]]  |yes |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  |no |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]  |no |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &2\\
f(3)= &9\\
f(4)= &\\
f(5)= &\\
f(6)= &\\
\end{array}$


====Subclasses====
[[Bounded residuated lattices]] subvariety

[[FLe-algebras]] subvariety

[[FLw-algebras]] subvariety

[[FLc-algebras]] subvariety

[[Distributive FL-algebras]] subvariety


====Superclasses====
[[Residuated lattices]] reduct


====References====

[(OK1985>
Hiroakira Ono, Yuichi Komori,
\emph{Logics without the contraction rule},
J. Symbolic Logic,
\textbf{50}1985, 169--201
[[MRreview]]
[[ZMATH]]
[[implementation]]
)]