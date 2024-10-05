=====m-zeroids=====

Abbreviation: **MZrd**


====Definition====
An \emph{m-zeroid} is a
algebra $\mathbf{A}=\langle A, \wedge, \vee, +, 0, -\rangle$ such that

$\langle A, +\rangle$ is a [[commutative semigroup]]

$\langle A, \wedge, \vee\rangle$ is a [[lattice]]

$-x=x$

$x + 0 = 0$

$x + -x = 0$

$x\le y\iff 0=-x+y$

$x + (y\vee z) = (x+y)\vee(x+z)$


==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be MV-algebras. A morphism from $\mathbf{A}
$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x+y)=h(x)+h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(x\vee y)=h(x)\vee h(y)$, $h(-x)=-h(x)$, $h(0)=0$

====Examples====
Example 1: 


====Basic results====

All subdirectly irreducible algebras are linearly ordered. 

The lattice is always bounded, with top element $0$. 

The bottom element $-0$ is the identity of $+$.

The dual operation $x\cdot y=-(-y+-x)$ is the fusion of a commutative integral involutive semilinear residuated lattice. In fact, m-zeroids are precisely the duals of these residuated lattices, which are also known as involutive IMTL algebras.

====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  | |
^[[Universal theory]]  | |
^[[First-order theory]]  | |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence e-regular]]  |yes, $e=1$ |
^[[Congruence uniform]]  | |
^[[Congruence extension property]]  | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |


====Finite members====

^$n$       | 1 | 2 | 3 | 4 | 5 | 6 |  7 |  8 |  9 |  10 |  11 |  12 |   13 |   14 |    15 |    16 |     17 |
^# of algs | 1 | 1 | 1 | 3 | 3 | 8 | 12 | 35 | 61 | 167 |     |     |      |      |       |       |        |
^# of si's | 0 | 1 | 1 | 2 | 3 | 7 | 12 | 31 | 59 | 161 | 329 | 944 | 2067 | 6148 | 14558 | 44483 | 116372 |

see http://oeis.org/A030453

====Subclasses====
[[TBD]] 


====Superclasses====
[[TBD]] 


====References====

J. B. Palmatier and F. Guzman,
\emph{M-zeroids structure and categorical equivalence},
Studia Logica,
\textbf{100}(5) 2012, 975--1000