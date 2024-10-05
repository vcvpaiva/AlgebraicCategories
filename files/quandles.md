=====Quandles=====

Abbreviation: **Qnd**

====Definition====
A \emph{quandle} is a structure $\mathbf{Q}=\langle Q,\triangleright,\triangleleft\rangle$ of type $\langle 2,2\rangle$ such that

$\triangleright$ is \emph{left-selfdistributive}:  $x\triangleright(y\triangleright z)=(x\triangleright y)\triangleright(x\triangleright z)$

$\triangleleft$ is \emph{right-selfdistributive}:  $(x\triangleleft y)\triangleleft z=(x\triangleleft z)\triangleleft(y\triangleleft z)$

$(x\triangleright y)\triangleleft x=y$

$x\triangleright (y\triangleleft x)=y$

$\triangleright$ is \emph{idempotent}: $x\triangleright x=x$

Remark: The last identity can equivalently be replaced by $\triangleleft$ is \emph{idempotent}: $x\triangleleft x=x$


==Morphisms==
Let $\mathbf{Q}$ and $\mathbf{R}$ be quandles. A morphism from $\mathbf{Q}$ to $\mathbf{R}$ is a function $h:Q\rightarrow R$ that is a homomorphism: 
$h(x \triangleright y)=h(x) \triangleright h(y)$ and $h(x \triangleleft y)=h(x) \triangleleft h(y)$.

====Examples====
Example 1: If $\langle G,\cdot,^{-1},1\rangle$ is a [[group]] and $x\triangleright y=xyx^{-1}$, $x\triangleleft y=x^{-1}yx$ (conjugation) then 
$\langle G,\triangleright,\triangleleft\rangle$ is a quandle.

====Basic results====


====Properties====
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.

^[[Classtype]]                        | [[variety]] |
^[[Equational theory]]                | |
^[[Quasiequational theory]]           | |
^[[First-order theory]]               | |
^[[Locally finite]]                   | |
^[[Residual size]]                    | |
^[[Congruence distributive]]          | No |
^[[Congruence modular]]               | No |
^[[Congruence $n$-permutable]]        | Yes, $n=2$ |
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
  f(2)= &1\\
  f(3)= &3\\
  f(4)= &7\\
  f(5)= &22\\
  f(6)= &73\\
  f(7)= &298\\
  f(8)= &1581\\
  f(9)= &11079\\
  f(10)= &\\
\end{array}$


====Subclasses====
[[Involutory quandles]]

[[Symmetric quandles]]

[[Abelian quandles]]

====Superclasses====
[[Racks]]

====References====

[(Lastname19xx>
F. Lastname, \emph{Title}, Journal, \textbf{1}, 23--45 [[MRreview]] 
)]


