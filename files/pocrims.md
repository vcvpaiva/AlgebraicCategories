=====Pocrims=====

Abbreviation: **Pocrim**

====Definition====
A \emph{pocrim} (short for \emph{partially ordered commutative residuated integral monoid}) is a structure $\mathbf{A}=\langle A,\oplus,\ominus,0\rangle$ of type $\langle 2,2,0\rangle$ such that

(1):  $((x \ominus y) \ominus (x \ominus z)) \ominus (z \ominus y) = 0$

(2):  $x \ominus 0 = x$

(3):  $0 \ominus x = 0$

(4):  $(x \ominus y) \ominus z = x \ominus (z \oplus y)$

(5):  $x \ominus y = y \ominus x = 0 \Longrightarrow x=y$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be pocrims. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \oplus y)=h(x) \oplus h(y)$,
$h(x \ominus y)=h(x) \ominus h(y)$,
$h(0)=0$.

====Definition====
A \emph{pocrim} is a structure $\mathbf{A}=\langle A,\oplus,\ominus,0\rangle$ such that

$\langle A,\ominus,0\rangle$ is a [[BCK-algebra]]

$(x \ominus y) \ominus z = x \ominus (z \oplus y)$

====Examples====
Example 1: 

====Basic results====


====Properties====
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.

^[[Classtype]]                        |quasivariety [(Higgs1984)]  |
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
1,1,2,7,26,129

$\begin{array}{lr}
  f(1)= &1\\
  f(2)= &1\\
  f(3)= &2\\
  f(4)= &7\\
  f(5)= &26\\
\end{array}$     
$\begin{array}{lr}
  f(6)= &129\\
  f(7)= &\\
  f(8)= &\\
  f(9)= &\\
  f(10)= &\\
\end{array}$


====Subclasses====
[[Hoops]]


====Superclasses====
[[Polrims]]

[[Commutative residuated partially ordered monoids]]

[[BCK-algebras]] reduced type


====References====

[(Higgs1984>
D. Higgs, \emph{Dually residuated commutative monoids with identity element as least element do not form an equational class}, Math. Japon., 
\textbf{29}, 1984, no. 1, 69--75 [[MRreview]] 
)]


