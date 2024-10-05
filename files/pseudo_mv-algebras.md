=====Pseudo MV-algebras=====

Abbreviation: **psMV**


====Definition====
A \emph{pseudo MV-algebra}[(GI2001)] (or \emph{psMV-algebra} for short) is a
structure $\mathbf{A}=\langle A, \oplus, ^-, ^\sim, 0, 1\rangle$ such that

$(x\oplus y)\oplus z = x\oplus(y\oplus z)$

$x\oplus 0 = x$

$x\oplus 1 = 1$

$(x^-\oplus y^-)^\sim = (x^\sim\oplus y^\sim)^-$

$(x\oplus y^\sim)^-\oplus x = y\oplus (x^-\oplus y)^\sim$

$x\oplus (y^-\oplus x)^\sim = y\oplus (x^-\oplus y)^\sim$

$x^{-\sim}=x$

$0^- = 1$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be pseudo MV-algebras. A morphism from $\mathbf{A}
$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x\oplus y)=h(x)\oplus h(y)$, $h(x^-)=h(x)^-$, $h(0)=0$ ($h(x^\sim)=h(x)^\sim$ and $h(1)=1$ follow from these).


====Examples====


====Basic results====
$0+x=x$, $1+x=1$, $x^{\sim-}=x$, $0^\sim=1$ and axiom A7 in[(GI2001)] follow from the above axioms.

Pseudo MV-algebras are term-equivalent to divisible [[involutive residuated lattices]].

Every psMV-algebra is obtained from an interval in a [[lattice-ordered group]][(Dvu2002)].

Every finite psMV-algebra is commutative.

Every commutative psMV-algebra is an [[MV-algebra]].

====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
^[[Quasiequational theory]]  |undecidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes |
^[[Congruence e-regular]]  |yes |
^[[Congruence uniform]]  |yes |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Amalgamation property]]  |  |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |


====Finite members====

^$n$       | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 | 24 | 25 |
^# of algs | 1 | 1 | 1 | 2 | 1 | 2 | 1 | 3 | 2 |  2 |  1 |  4 |  1 |  2 |  2 |  5 |  1 |  4 |  1 |  4 |  2 |  2 |  1 |  7 |  2 |
^# of si's | 0 | 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |  1 |

====Subclasses====
[[MV-algebras]] 


====Superclasses====

[[Involutive residuated lattices]]

====References====

[(GI2001>
S. Georgescu and A. Iorgulescu, 
\emph{Pseudo-MV algebras}, 
Multiple Valued Logic, \textbf{6}, 2001, 95--135)]

[(Dvu2002>
A. Dvurecenskij,
\emph{Pseudo MV-algebras are intervals in $\ell$-groups}, Journal of the Australian Mathematical Soc.
Ser. 72, (2002), 427-–445)]