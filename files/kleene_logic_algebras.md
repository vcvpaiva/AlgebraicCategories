=====Kleene logic algebras=====

Abbreviation: **KLA**
====Definition====
A \emph{Kleene logic algebra} is a [[De Morgan algebra]] $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\neg\rangle $ that satisfies


$x\wedge \neg x\le y\vee \neg y$.


Remark: Also called Kleene algebras, but this name more commonly refers to the algebraic models of regular languages.

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Kleene logic algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(\neg x)=\neg h(x)$
====Examples====
Example 1: Let $\{0<a<1\}$ be the 3-element lattice with $0'=1,a'=a,b'=b$.
====Basic results====

The algebra in Example 1 generates the variety of Kleene logic algebras

====Properties====
^[[Classtype]]  |Variety |
^[[Equational theory]]  |Decidable |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  | |
^[[Congruence distributive]]  |Yes |
^[[Congruence modular]]  |Yes |
^[[Congruence n-permutable]]  | |
^[[Congruence regular]]  | |
^[[Congruence uniform]]  | |
^[[Congruence extension property]]  |Yes |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |
^[[Locally finite]]  |Yes |
^[[Residual size]]  | 3 |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &1\\
f(6)= &3\\
f(7)= &2\\
f(8)= &6\\
f(9)= &4\\
f(10)= &10\\
\end{array}$

====Subclasses====
[[Boolean algebras]] 

====Superclasses====
[[De Morgan algebras]] 


====References====

[(Ln19xx>
)]