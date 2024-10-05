=====Kleene algebras=====

Abbreviation: **KA**
====Definition====
A \emph{Kleene algebra} is a structure $\mathbf{A}=\langle A,\vee
,0,\cdot ,1,^{\ast }\rangle $ of type $\langle
2,0,2,0,1\rangle $ such that
$\langle A,\vee ,0,\cdot ,1\rangle $ is an [[idempotent semiring with identity and zero]]

$e\vee x\vee x^{\ast }x^{\ast }=x^{\ast }$

$xy\leq y\Longrightarrow x^{\ast }y=y$

$yx\leq y\Longrightarrow yx^{\ast }=y$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Kleene algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a
homomorphism: $h(x\vee y)=h(x)\vee h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x^{\ast })=h(x)^{\ast }$, $h(0)=0$,
and $h(1)=1$.

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |quasivariety |
^[[Equational theory]]  |decidable, PSPACE complete [(StoMey1973)] |
^[[Quasiequational theory]]  |undecidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |no |
^[[Congruence modular]]  |no |
^[[Congruence meet-semidistributive]]  |yes |
^[[Congruence n-permutable]]  |no |
^[[Congruence regular]]  |no |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |


====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &3\\
f(4)= &20\\
f(5)= &149\\
f(6)= &1488\\
\end{array}$


====Subclasses====
[[Action algebras]] 

[[Kleene lattices]] 


====Superclasses====
[[Idempotent semirings with identity and zero]] 

====References====

[(StoMey1973>
L. J. Stockmeyer, A. R. Meyer, \emph{Word problems requiring exponential time: preliminary report},
Fifth Annual ACM Symposium on Theory of Computing (Austin, Tex., 1973),
Assoc. Comput. Mach., New York, 1973, 1--9 
[[MRreview]][[ZMATH]]
)]