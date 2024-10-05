=====Hilbert algebras=====

Abbreviation: **HilA**

====Definition====
A \emph{Hilbert algebra} is a structure $\mathbf{A}=\langle A,\to,1\rangle$ of type $\langle 2, 1\rangle$ such that

$x\to(y\to x)=1$

$(x\to(y\to z))\to((x\to y)\to(x\to z))=1$

$x\to y=1\mbox{ and }y\to x=1 \Longrightarrow x=y$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Hilbert algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x\to y)=h(x)\to h(y)$ and $h(1)=1$.

====Definition====
A \emph{Hilbert algebra} is a structure $\mathbf{A}=\langle A,\to,1\rangle$ of type $\langle 2, 1\rangle$ such that

$x\to x=1$

$1\to x=x$

$x\to(y\to z)=(x\to y)\to(x\to z)$

$(x\to y)\to((y\to x)\to x)=(y\to x)\to((x\to y)\to y)$

====Examples====
Example 1: Given any poset with top element 1, $\langle A,\le, 1\rangle$, define $a\to b=\begin{cases}1&\text{ if $a\le b$}\\ b&\text{ otherwise.}\end{cases}$ Then $\langle A,\to,1\rangle$ is a Hilbert algebra.

====Basic results====

Hilbert algebras are the algebraic models of the implicational fragment of [[wp>intuitionistic logic]], i.e., they are $(\to,1)$-subreducts of [[Heyting algebras]].

The variety of Hilbert algebras is not generated as a quasivariety by any of its finite members [(CelaniCabrer2005)].

====Properties====

^[[Classtype]]                        |variety [(Diego1966)]  |
^[[Equational theory]]                | |
^[[Quasiequational theory]]           | |
^[[First-order theory]]               | |
^[[Locally finite]]                   | |
^[[Residual size]]                    | |
^[[Congruence distributive]]          | |
^[[Congruence modular]]               | |
^[[Congruence $n$-permutable]]        | |
^[[Congruence regular]]               | |
^[[Congruence uniform]]               | |
^[[Congruence extension property]]    | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]      | |
^[[Amalgamation property]]            | |
^[[Strong amalgamation property]]     | |
^[[Epimorphisms are surjective]]      | |

====Finite members====

$\begin{array}{lr}
  f(1)= &1\\
  f(2)= &\\
  f(3)= &\\
  f(4)= &\\
  f(5)= &\\
\end{array}$     
$\begin{array}{lr}
  f(6)= &\\
  f(7)= &\\
  f(8)= &\\
  f(9)= &\\
  f(10)= &\\
\end{array}$


====Subclasses====
[[...]] subvariety

[[...]] expansion


====Superclasses====
[[...]] supervariety

[[...]] subreduct


====References====

[(Diego1966>
A. Diego, \emph{Sur les algébres de Hilbert}, Collection de Logique Math\'ematique, S\'er. A, 1966, 1--55
)]

[(CelaniCabrer2005>
S. Celani and L. Cabrer: Duality for finite Hilbert algebras. Discrete Math. 305 (2005), no. 1-3, 74-–99.
)]


