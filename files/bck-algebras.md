=====BCK-algebras=====

Abbreviation: **BCK**
====Definition====
A \emph{BCK-algebra} is a structure $\mathbf{A}=\langle A,\cdot ,0\rangle$ of type $\langle 2,0\rangle$ such that

(1):  $((x\cdot y)\cdot (x\cdot z))\cdot (z\cdot y) = 0$

(2):  $x\cdot 0 = x$

(3):  $0\cdot x = 0$

(4):  $x\cdot y=y\cdot x= 0 \Longrightarrow x=y$

Remark: 
$x\le y \iff x\cdot y=0$ is a partial order, with $0$ as least element.

BCK-algebras provide [[algebraic semantics]] for BCK-logic, named after
the combinators B, C, and K by C. A. Meredith, see [(Prior1962)].

====Definition====
A \emph{BCK-algebra} is a [[BCI-algebra]] 
$\mathbf{A}=\langle A,\cdot ,0\rangle$ such that

$x\cdot 0 = x$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be BCK-algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x\cdot y)=h(x)\cdot h(y)$ and $h(0)=0$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]                        |quasivariety [(Wronski1983)] |
^[[Equational theory]]                | |
^[[Quasiequational theory]]           | |
^[[First-order theory]]               |undecidable |
^[[Locally finite]]                   |no |
^[[Residual size]]                    |unbounded |
^[[Congruence distributive]]          |no |
^[[Congruence modular]]               |no |
^[[Congruence n-permutable]]          |no |
^[[Congruence regular]]               |no |
^[[Congruence uniform]]               |no |
^[[Congruence extension property]]    |no |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]      |no |
^[[Amalgamation property]]            |yes |
^[[Strong amalgamation property]]     |yes [(Wronski1984)] |
^[[Epimorphisms are surjective]]      | |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &3\\
f(4)= &14\\
f(5)= &88\\
f(6)= &775\\
\end{array}$

====Subclasses====
[[Commutative BCK-algebras]] 

====Superclasses====
[[BCI-algebras]] 


====References====

[(Prior1962>
A. N. Prior, \emph{Formal logic},
Second edition, Clarendon Press, Oxford, 1962, p.316)]

[(Wronski1983>
Andrzej Wronski,\emph{BCK-algebras do not form a variety},
Math. Japon., \textbf{28}, 1983, 211--213)]

[(Wronski1984>
Andrzej Wronski,\emph{Interpolation and amalgamation properties of BCK-algebras},
Math. Japon., \textbf{29}, 1984, 115--121)]




