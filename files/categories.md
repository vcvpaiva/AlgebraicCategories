=====Categories=====

Abbreviation: **Cat**

====Definition====
A \emph{category} is a structure $\mathbf{C}=\langle C,\circ,\text{dom},\text{cod}\rangle$ of type $\langle 2,1,1\rangle$ such that
$C$ is a class,

$\langle C,\circ\rangle$ is a (large) [[partial semigroup]]

dom amd cod are total unary operations on $C$ such that

$\text{dom}(x)$ is a left unit:  $\text{dom}(x)\circ x=x$

$\text{cod}(x)$ is a right unit:  $x\circ\text{cod}(x)=x$

if $x\circ y$ exists then $\text{dom}(x\circ y)=\text{dom}(x)$ and $\text{cod}(x\circ y)=\text{cod}(y)$

$x\circ y$ exists iff $\text{cod}(x)=\text{dom}(y)$

Remark: The members of $C$ are called \emph{morphisms}, $\circ$ is the partial operation of \emph{composition},
dom is the \emph{domain} and cod is the \emph{codomain} of a morphism.

The set of objects of $C$ is the set $\mathbf{Obj}C=\{\text{dom}(x)|x\in C\}$. For $a,b\in C$ the set of homomorphism from $a$ to $b$ is
$\text{Hom}(a,b)=\{c\in C|\text{dom}(c)=a\text{ and }\text{cod}(c)=b\}$.

==Morphisms==
Let $\mathbf{C}$ and $\mathbf{D}$ be categories. A morphism from $\mathbf{C}$ to $\mathbf{D}$ is a function $h:C\rightarrow D$ that is a homomorphism: 
$h(\text{dom}(c))=\text{dom}h(c)$, $h(\text{cod}(c))=\text{cod}h(c)$ and
$h(c\circ d)=h(c) \circ h(d)$ whenever $c\circ d$ is defined.

Morphisms between categories are called \emph{functors}.

====Examples====
Example 1: The category of function on sets with composition.

In fact, most of the classes of mathematical structures in this database are categories.

====Basic results====

$\text{dom}(\text{dom}(x))=\text{dom}(x)=\text{cod}(\text{dom}(x))$

$\text{cod}(\text{cod}(x))=\text{cod}(x)=\text{dom}(\text{cod}(x))$

====Properties====

^[[Classtype]]                        |many-sorted variety  |
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
  f(2)= &3\\
  f(3)= &11\\
  f(4)= &55\\
  f(5)= &329\\
  f(6)= &2858\\
  f(7)= &\\
  f(8)= &\\
  f(9)= &\\
  f(10)= &\\
\end{array}$

http://oeis.org/A125696

====Subclasses====
[[Schroeder categories]]

[[Closed categories]]

[[Compact categories]]


====Superclasses====
[[Partially ordered categories]]

[[Partial semigroups]]


====References====

[(Ln19xx>
F. Lastname, \emph{Title}, Journal, \textbf{1}, 23--45 [[MRreview]] 
)]


