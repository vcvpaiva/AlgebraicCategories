=====Commutative involutive FL-algebras=====

Abbreviation: **CInFL**

====Definition====
A \emph{commutative involutive FL-algebra} or \emph{commutative involutive residuated lattice} is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee, \wedge\rangle$ is a [[lattice]]

$\langle A, \cdot, 1\rangle$ is a [[commutative monoid]]

$\sim$ is an \emph{involution}: ${\sim}{\sim}x=x$ and

$xy\le z\iff x\le {\sim}(y({\sim}z))$

====Definition====
A \emph{commutative involutive FL-algebra} or \emph{commutative involutive residuated lattice} is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee\rangle$ is a [[semilattice]]

$\langle A, \cdot\rangle$ is a [[commutative semigroup]] and

$x\le z\iff x\cdot{\sim}y\le{\sim}1$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be involutive residuated lattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$, $h(x \cdot y)=h(x) \cdot h(y)$, $h({\sim}x)={\sim}h(x)$ and $h(1)=1$. 

====Examples====
Example 1: 

====Basic results====


====Properties====

^[[Classtype]]                        |Value  |
^[[Equational theory]]                |Decidable [(GalatosJipsen2012)] |
^[[Quasiequational theory]]           | |
^[[First-order theory]]               | |
^[[Locally finite]]                   |No |
^[[Residual size]]                    |$\infty$ |
^[[Congruence distributive]]          |Yes |
^[[Congruence modular]]               |Yes |
^[[Congruence $n$-permutable]]        | |
^[[Congruence regular]]               | |
^[[Congruence uniform]]               | |
^[[Congruence extension property]]    | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]      |No |
^[[Amalgamation property]]            | |
^[[Strong amalgamation property]]     | |
^[[Epimorphisms are surjective]]      | |

====Finite members====

$\begin{array}{lr}
  f(1)= &1\\
  f(2)= &1\\
  f(3)= &2\\
  f(4)= &9\\
  f(5)= &21\\
\end{array}$     
$\begin{array}{lr}
  f(6)= &100\\
  f(7)= &276\\
  f(8)= &1392\\
  f(9)= &\\
  f(10)= &\\
\end{array}$


====Subclasses====
[[Commutative idempotent involutive FL-algebras]] subvariety

====Superclasses====
[[Cyclic involutive FL-algebras]] supervariety


====References====

[(GalatosJipsen2012>
N. Galatos and P. Jipsen, \emph{Residuated frames with applications}, 
Transactions of the AMS, 365 (2013), 1219-1249)]


