=====Partial groupoids=====

Abbreviation: **Pargoid**

====Definition====
A \emph{partial groupoid} is a structure $\mathbf{A}=\langle A,\cdot\rangle$, where 

$\cdot$ is a \emph{partial binary operation}, i.e., $\cdot: A\times A\to A+\{*\}$.

Remark: The domain of definition of $\cdot$ is Dom$(\cdot)=\{\langle x,y\rangle\in A^2 \mid x\cdot y\ne *\}$ 

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be partial groupoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
if $x\cdot y\ne *$ then $h(x \cdot y)=h(x) \cdot h(y)$

====Examples====
Example 1: The empty partial binary operation on any set $A$ gives a partial groupoid.

====Basic results====


====Properties====

^[[Classtype]]                        |first-order  |
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
  f(1)= &2\\
  f(2)= &45\\
  f(3)= &43968\\
  f(4)= &6358196250\\
  f(5)= &236919104155855296\\
\end{array}$     

See http://oeis.org/A090601

====Subclasses====
[[Groupoids]]

[[Partial semigroups]]


====Superclasses====
[[Ternary relations]]


====References====

[(Ljapin1997>
E. S. Ljapin and A. E. Evseev, \emph{The theory of partial algebraic operations}, Kluwer, 1997 
)]


