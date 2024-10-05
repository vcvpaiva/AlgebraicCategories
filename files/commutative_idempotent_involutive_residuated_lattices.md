=====Commutative idempotent involutive FL-algebras=====

Abbreviation: **CIdInFL**

====Definition====
A \emph{commutative idempotent involutive FL-algebra} or \emph{commutative idempotent involutive residuated lattice} is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee, \wedge\rangle$ is a [[lattice]]

$\langle A, \cdot, 1\rangle$ is a [[semilattice]] with top

$\sim$ is an \emph{involution}: ${\sim}{\sim}x=x$ and

$xy\le z\iff x\le {\sim}(y({\sim}z))$

====Definition====
A \emph{commutative involutive FL-algebra} or \emph{commutative involutive residuated lattice} is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee\rangle$ is a [[semilattice]]

$\langle A, \cdot\rangle$ is a [[semilattice]] and

$x\le z\iff x\cdot{\sim}y\le{\sim}1$, where $x\le y\iff x\vee y=y$.

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
  f(3)= &1\\
  f(4)= &2\\
  f(5)= &2\\
  f(6)= &4\\
  f(7)= &4\\
  f(8)= &9\\
  f(9)= &10\\
  f(10)= &21\\
  f(11)= &22\\
  f(12)= &49\\
  f(13)= &52\\
  f(14)= &114\\
  f(15)= &121\\
  f(16)= &270\\
\end{array}$


====Subclasses====
[[Sugihara algebras]] subvariety

====Superclasses====
[[Commutative involutive FL-algebras]] supervariety


====References====

[(GalatosJipsen2012> N. Galatos and P. Jipsen, \emph{Residuated frames with applications}, Transactions of the AMS, 365 (2013), 1219-1249 )]


