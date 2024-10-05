=====Residuated lattices=====

Abbreviation: **RL**

====Definition====
A \emph{residuated lattice} is a structure $\mathbf{L}=\langle L, \vee, \wedge, \cdot, e, \backslash, /\rangle$ of type $\langle
2,2,2,0,2,2\rangle$ such that

$\langle L, \cdot, e\rangle$ is a [[monoid]]

$\langle L, \vee, \wedge\rangle$ is a [[lattice]]

$\backslash$ is the left residual of $\cdot$: $y\leq x\backslash z\Longleftrightarrow xy\leq z$

$/$ is the right residual of $\cdot$: $x\leq z/y\Longleftrightarrow xy\leq z$

==Morphisms==
Let $\mathbf{L}$ and $\mathbf{M}$ be residuated lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\rightarrow M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash
y)=h(x)\backslash h(y)$, $h(x/y)=h(x)/h(y)$, $h(e)=e$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]                        |variety |
^[[Equational theory]]                |decidable [(OK1985)] [[implementation]] |
^[[Quasiequational theory]]           |undecidable |
^[[First-order theory]]               |undecidable |
^[[Locally finite]]                   |no |
^[[Residual size]]                    |unbounded |
^[[Congruence distributive]]          |yes |
^[[Congruence modular]]               |yes |
^[[Congruence n-permutable]]          |yes, $n=2$ |
^[[Congruence regular]]               |no |
^[[Congruence e-regular]]             |yes |
^[[Congruence uniform]]               |no |
^[[Congruence extension property]]    |no |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]      |no |
^[[Amalgamation property]]            | |
^[[Strong amalgamation property]]     | |
^[[Epimorphisms are surjective]]      | |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &3\\
f(4)= &20\\
f(5)= &149\\
f(6)= &1488\\
f(7)= &18554\\
f(8)= &295292\\
\end{array}$

[[Small residuated lattices]]


====Subclasses====
[[Commutative residuated lattices]] 

[[Distributive residuated lattices]] 

[[FL-algebras]] 

[[Integral residuated lattices]] 

====Superclasses====
[[Multiplicative lattices]] 

[[Residuated join-semilattices]] 

[[Residuated meet-semilattices]] 


====References====

[(OK1985>
Hiroakira Ono, Yuichi Komori, \emph{Logics without the contraction rule},
J. Symbolic Logic, \textbf{50}, 1985, 169--201 [[MRreview]][[ZMATH]]
)]\end{document}
%</pre>
