=====Distributive lattice-ordered semigroups=====

Abbreviation: **DLOS**

====Definition====
A \emph{distributive lattice ordered semigroup} is a structure $\mathbf{A}=\langle A,\vee,\wedge,\cdot\rangle$ of type $\langle 2,2,2\rangle$ such that

$\langle A,\vee,\wedge\rangle$ is a [[distributive lattice]]

$\langle A,\cdot\rangle$ is a [[semigroup]]

$\cdot$ distributes over $\vee$:  $x\cdot(y\vee z)=(x\cdot y)\vee (x\cdot z)$ and $(x\vee y)\cdot z=(x\cdot z)\vee (y\cdot z)$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be distributive lattice-ordered semigroups. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x\vee y)=h(x) \vee h(y)$,
$h(x\wedge y)=h(x) \wedge h(y)$,
$h(x\cdot y)=h(x) \cdot h(y)$

====Examples====
Example 1: Any collection $\mathbf A$ of binary relations on a set $X$ such that $\mathbf A$ is closed under union, intersection and composition.

H. Andreka[(Andreka1991)] proves that these examples generate the variety DLOS.

====Basic results====


====Properties====
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.

^[[Classtype]]                        |variety  |
^[[Equational theory]]                | |
^[[Quasiequational theory]]           | |
^[[First-order theory]]               | |
^[[Locally finite]]                   | |
^[[Residual size]]                    | |
^[[Congruence distributive]]          |yes |
^[[Congruence modular]]               |yes |
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
  f(2)= &6\\
  f(3)= &44\\
  f(4)= &479\\
  f(5)= &\\
\end{array}$

====Subclasses====
[[Distributive lattice-ordered monoids]]

[[Commutative distributive lattice-ordered semigroups]]

====Superclasses====
[[Lattice-ordered semigroups]]

====References====

[(Andreka1991>Hajnal Andreka, \emph{Representations of distributive lattice-ordered semigroups with binary relations}, Algebra Universalis \textbf{28} (1991), 12--25)]


