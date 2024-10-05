=====Partial semigroups=====

Abbreviation: **PSgrp**

====Definition====
A \emph{partial semigroup} is a structure $\mathbf{A}=\langle A,\cdot\rangle$, where 

$\cdot$ is a \emph{partial binary operation}, i.e., $\cdot: A\times A\to A+\{*\}$ and

$\cdot$ is \emph{associative}: $(x\cdot y)\cdot z\ne *$ or $x\cdot (y\cdot z)\ne *$ imply $(x\cdot y)\cdot z=x\cdot (y\cdot z)$.


==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be partial groupoids. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
if $x\cdot y\ne *$ then $h(x \cdot y)=h(x) \cdot h(y)$

====Examples====
Example 1: The morphisms is a small category under composition.

====Basic results====
Partial semigroups can be identified with [[semigroups with zero]] since for any partial semigroup $A$ we can define a semigroup $A_0=A\cup\{0\}$ (assuming $0\notin A$)
and extend the operation on $A$ to $A_0$ by $0x=0=x0$ for all $x\in A$. Conversely, given a semigroup with zero, say $B$, define a partial semigroup 
$A=B\setminus\{0\}$ and for $x,y\in A$ let $xy=*$ if $xy=0$ in $B$. These two maps are inverses of each other. 

However, the category of partial semigroups is not the same as the category of semigroups with zero since the morphisms differ.

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

http://mathv.chapman.edu/~jipsen/uajs/PSgrp.html 

$\begin{array}{lr}
  f(1)= &2\\
  f(2)= &12\\
  f(3)= &90\\
  f(4)= &960\\
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
[[Semigroups]]

[[Partial monoids]]


====Superclasses====
[[Partial groupoids]]


====References====


