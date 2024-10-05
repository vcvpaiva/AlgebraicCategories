=====Monadic algebras=====

Abbreviation: **MonA**

====Definition====
A \emph{monadic algebra} is a structure $\mathbf{A}=\langle A, \vee, 0, \wedge, 1, \neg, f\rangle$ of type $\langle 2, 0, 2, 0, 1, 1\rangle$ such that

$\langle A, \vee, 0, \wedge, 1, \neg\rangle$ is a [[Boolean algebra]]

$f$ is a \emph{unary closure operator}:  $f(x\vee y)=f(x)\vee f(y)$, $f(0)=0$, $x\le f(x)=f(f(x))$

$f$ is \emph{self conjugated}:  $f(x)\wedge y=0\iff x\wedge f(y)=0$

Remark: This is a template.
If you know something about this class, click on the 'Edit text of this page' link at the bottom and fill out this page.

It is not unusual to give several (equivalent) definitions. Ideally, one of the definitions would give an irredundant axiomatization that does not refer to other classes.

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be monodic algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 
$h(x \vee y)=h(x) \vee h(y)$,
$h(\neg x)=\neg h(x)$, 
$h(f(x))=f(h(x))$.

====Definition====
An \emph{...} is a structure $\mathbf{A}=\langle A,...\rangle$ of type $\langle
...\rangle$ such that

$...$ is ...:  $axiom$
  
$...$ is ...:  $axiom$

====Examples====
Example 1: 

====Basic results====


====Properties====
Feel free to add or delete properties from this list. The list below may contain properties that are not relevant to the class that is being described.

^[[Classtype]]                        |variety  |
^[[Equational theory]]                |decidable |
^[[Quasiequational theory]]           | |
^[[First-order theory]]               | |
^[[Locally finite]]                   | |
^[[Residual size]]                    | |
^[[Congruence distributive]]          |yes |
^[[Congruence modular]]               |yes |
^[[Congruence $n$-permutable]]        |yes, $n=2$ |
^[[Congruence regular]]               |yes |
^[[Congruence uniform]]               |yes |
^[[Congruence extension property]]    |yes |
^[[Definable principal congruences]]  |yes |
^[[Equationally def. pr. cong.]]      |yes |
^[[Amalgamation property]]            |yes |
^[[Strong amalgamation property]]     | |
^[[Epimorphisms are surjective]]      | |

====Finite members====

$\begin{array}{lr}
  f(1)= &1\\
  f(2)= &1\\
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
  [[Boolean algebras]] reduced type

  [[Closure algebras]]


====References====

[(Lastname19xx>
F. Lastname, \emph{Title}, Journal, \textbf{1}, 23--45 [[MRreview]] 
)]


