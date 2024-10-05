=====Action algebras=====

Abbreviation: **Act**
====Definition====
An \emph{action algebra} is a structure $\mathbf{A}=\langle A,\vee,\bot,\cdot,1,^*,\backslash,/\rangle$ of type 
$\langle 2,0,2,0,1,2,2\rangle$ such that


$\langle A,\vee,\bot,\cdot,1,^*\rangle$ is a [[Kleene algebra]]


$\backslash $ is the left residual of $\cdot$:  $y\leq x\backslash z\Longleftrightarrow xy\leq z$


$/$ is the right residual of $\cdot$:  $x\leq z/y\Longleftrightarrow xy\leq z$


Remark: These equivalences can be written equationally.


==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be action algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 
$h(x\vee y)=h(x)\vee h(y)$, $h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash y)=h(x)\backslash h(y)$,
$h(x/y)=h(x)/h(y)$, $h(x^*)=h(x)^*$, $h(\bot)=\bot$ and $h(1)=1$.

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety [(Pratt1991)] |
^[[Equational theory]]  | |
^[[Quasiequational theory]]  |undecidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes [(AltRaf2004)] |
^[[Congruence modular]]  |yes  |
^[[Congruence n-permutable]]  |yes, $n=4$ [(AltRaf2004)] |
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
f(2)= &1\\
f(3)= &3\\
f(4)= &20\\
f(5)= &149\\
f(6)= &1488
\end{array}$


====Subclasses====
[[Action lattices]] 

====Superclasses====
[[Kleene algebras]] 

[[Residuated join-semilattices]] 


====References====

[(Pratt1991>
Vaughan Pratt, \emph{Action logic and pure induction},
``Logics in AI (Amsterdam, 1990)'', Lecture Notes in Comput. Sci.,
478, 1991, 97--120, 92d:03016)]

[(AltRaf2004>
C.J. van Alten and J.G. Raftery, \emph{Embedding Theorems and Rule Separation in Logics without Weakening},
Studia Logica, 2004, ...--..., [[preprint]]
)]
