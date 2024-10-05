=====Quantales=====

Abbreviation: **Quant**

====Definition====
A \emph{quantale} is a structure $\mathbf{A}=\langle A, \bigvee, \cdot, 0\rangle$ of type $\langle\infty, 2, 0\rangle$ such that

$\langle A, \bigvee, 0\rangle$ is a [[complete semilattice]] with $0=\bigvee\emptyset$,

$\langle A, \cdot\rangle$ is a [[semigroup]], and

$\cdot$ distributes over $\bigvee$:  $(\bigvee X)\cdot y=\bigvee_{x\in X}(x\cdot y)$ and $y\cdot(\bigvee X)=\bigvee_{x\in X}(y\cdot x)$


Remark: In particular, $\cdot$ distributes over the empty join, so $x\cdot 0=0=0\cdot x$.

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be quantales. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(\bigvee X)=\bigvee h[X]$ for all $X\subseteq A$ (hence $h(0)=0$) and
$h(x \cdot y)=h(x) \cdot h(y)$



====Examples====
Example 1: 

====Basic results====


====Properties====
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.

^[[Classtype]]                        |(value, see description) [(Ln19xx)]  |
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
  f(2)= &2\\
  f(3)= &12\\
  f(4)= &129\\
  f(5)= &1852\\
  f(6)= &33391\\
\end{array}$

Model search done by Mace4 https://www.cs.unm.edu/~mccune/mace4/

====Subclasses====
  [[...]] subvariety

  [[...]] expansion


====Superclasses====
  [[...]] supervariety

  [[...]] subreduct


====References====

[(Ln19xx>
F. Lastname, \emph{Title}, Journal, \textbf{1}, 23--45 [[MRreview]] 
)]


