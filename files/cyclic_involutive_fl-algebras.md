=====Cyclic involutive FL-algebras=====

Abbreviation: **CyInFL**

====Definition====
A \emph{cyclic involutive FL-algebra} or \emph{cyclic involutive residuated lattice} is a structure $\mathbf{A}=\langle A, \vee, \wedge, \cdot, 1, \sim\rangle$ of type $\langle 2, 2, 2, 0, 1\rangle$ such that

$\langle A, \vee, \wedge\rangle$ is a [[lattice]]

$\langle A, \cdot, 1\rangle$ is a [[monoid]]

$\sim$ is an \emph{involution}: ${\sim}{\sim}x=x$ and

$xy\le z\iff x\le {\sim}(y({\sim}z))\iff y\le {\sim}(({\sim}z)x)$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be involutive residuated lattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$, $h(x \cdot y)=h(x) \cdot h(y)$, $h({\sim}x)={\sim}h(x)$ and $h(1)=1$. 

====Definition====
An \emph{involutive FL-algebra} is an [[FL-algebra]] $\mathbf{A}=\langle A,\vee,\wedge,\cdot,1,\backslash,/,0\rangle$ such that

cyclic involution holds: $(0/x)\backslash 0=x=0/(x\backslash 0)$ and $0/x=x\backslash 0$

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
  f(6)= &101\\
  f(7)= &279\\
  f(8)= &1433\\
  f(9)= &\\
  f(10)= &\\
\end{array}$


====Subclasses====
[[Cyclic integral involutive FL-algebras]] subvariety

====Superclasses====
[[involutive FL-algebras]] supervariety


====References====

[(GalatosJipsen>
N. Galatos and P. Jipsen, \emph{Residuated frames with applications}, Transactions of the AMS, 365 (2013), 1219-1249 
)]


