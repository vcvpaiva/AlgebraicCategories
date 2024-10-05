=====MV-algebras=====

Abbreviation: **MV**


====Definition====
An \emph{MV-algebra} (short for \emph{multivalued logic algebra}) is a
structure $\mathbf{A}=\langle A, +, 0, \neg\rangle$ such that

$\langle A, +, 0\rangle$ is a [[commutative monoid]]

$\neg \neg x=x$

$x + \neg 0 = \neg 0$

$\neg(\neg x+y)+y = \neg(\neg y+x)+x$

Remark: This is the definition from [(COM2000)]


==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be MV-algebras. A morphism from $\mathbf{A}
$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x+y)=h(x)+h(y)$, $h(\neg x)=\neg h(x)$, $h(0)=0$


====Definition====
An \emph{MV-algebra} is a
structure $\mathbf{A}=\langle A, +, 0, \cdot, 1, \neg\rangle$ such that

$\langle A, \cdot, 1\rangle$ is a [[commutative monoid]]

$\neg $ is a DeMorgan involution for $+,\cdot $:  $\neg \neg x=x$, $x+y=\neg ( \neg x\cdot \neg y)$

$\neg 0=1$, $0\cdot x=0$, $\neg ( \neg x+y) +y=\neg ( \neg y+x) +x$


====Definition====
An \emph{MV-algebra} is a [[basic logic algebra]] $\mathbf{A}=\langle
A,\vee,0,\wedge,1,\cdot,\to\rangle$ that satisfies

MV:  $x\vee y=(x\to y)\to y$


====Definition====
A \emph{Wajsberg algebra} is an algebra $\mathbf{A}=\langle A, \to, \neg, 1\rangle$ such that

$1\to x=x$

$(x\to y)\to((y\to z)\to(x\to z) = 1$

$(x\to y)\to y = (y\to x)\to x$

$(\neg x\to\neg y)\to(y\to x)=1$

Remark: 
Wajsberg algebras are term-equivalent to MV-algebras via $x\to y=\neg x+y$, $1=\neg 0$ and $x + y=\neg x\to y$, $0=\neg 1$.


====Definition====
A \emph{bounded Wajsberg hoop} is an algebra $\mathbf{A}=\langle A, \cdot, \to, 0, 1\rangle$ such that

$\langle A, \cdot, \to, 1\rangle$ is a [[hoop]]

$(x\to y)\to y = (y\to x)\to x$

$0\to x=1$

Remark: 
Bounded Wajsberg hoops are term-equivalent to Wajsberg algebras via $x\cdot y=\neg(x\to\neg y)$, $0=\neg 1$, and $\neg x=x\to 0$.
See [(BP1994)] for details.


====Definition====
A \emph{lattice implication algebra} is an algebra $\mathbf{A}=\langle A, \to, -, 1\rangle$ such that

$x\to (y\to z) = y\to (x\to z)$

$1\to x = x$

$x\to 1 = 1$

$x\to y = {-}y\to {-}x$

$(x\to y)\to y = (y\to x)\to x$

Remark: 
Lattice implication algebras are term-equivalent to MV-algebras via $x + y = -x\to y$, $0 = -1$, and $\neg x= - x$.

====Definition====
A \emph{bounded commutative BCK-algebra} is an algebra $\mathbf{A}=\langle A,\cdot, 0, 1\rangle$ such that

$\langle A,\cdot,0\rangle$ is a [[commutative BCK-algebra]] and

$x\cdot 1 = 0$

Remark: 
Bounded commutative BCK-algebras are term-equivalent to MV-algebras via $\neg x=1\cdot x$, $x + y = y\cdot \neg x$, and switching the role of $0$, $1$.

====Examples====
Example 1: 


====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
^[[Universal theory]]  |decidable (FEP[(BF2000)])|
^[[First-order theory]]  | |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence e-regular]]  |yes, $e=1$ |
^[[Congruence uniform]]  | |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  |no |
^[[Amalgamation property]]  |yes [(Mu1987)] |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |


====Finite members====

^$n$       | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 |
^# of algs | 1 | 1 | 1 | 2 | 1 | 2 | 1 | 3 | 2 |  2 |  1 |  4 |  1 |  2 |  2 |  5 |  1 |  4 |  1 |  4 |  2 |  2 |  1 |  7 |  2 |
^# of si's | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |

The number of algebras with $n$ elements is given by the number of ways of factoring $n$ into a product with nontrivial factors,
see http://oeis.org/A001055

====Subclasses====
[[Boolean algebras]] 


====Superclasses====
[[Generalized MV-algebras]] 

[[Basic logic algebras]] 

[[Wajsberg hoops]] 


====References====

[(BF2000>
W. J. Blok, I. M. A. Ferreirim,
\emph{On the structure of hoops},
Algebra Universalis,
\textbf{43} 2000, 233--257)]

[(BP1994>
W. J. Blok, D. Pigozzi,
\emph{On the structure of varieties with equationally definable principal congruences. III},
Algebra Universalis,
\textbf{32} 1994, 545--608)]

[(COM2000>
Roberto L. O. Cignoli, Itala M. L. D'Ottaviano, Daniele Mundici,
\emph{Algebraic foundations of many-valued reasoning},
Trends in Logic---Studia Logica Library
\textbf{7} Kluwer Academic Publishers
2000, x+231)]

[(Mu1987>
Daniele Mundici,
\emph{Bounded commutative BCK-algebras have the amalgamation property},
Math. Japon.,
\textbf{32} 1987, 279--282)]
