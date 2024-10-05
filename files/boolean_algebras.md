=====Boolean algebras=====

Abbreviation: **BA** nbsp nbsp nbsp nbsp nbsp Search: [[http://www.google.com/search?q=boolean+algebras|Boolean algebras]]
[[http://www.google.com/search?q=boolean+rings|Boolean rings]]

====Definition====
A \emph{Boolean algebra} is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,-\rangle $ of type $\langle 2,0,2,0,1\rangle $
such that

$0,1$ are identities for $\vee,\wedge$:  $x\vee 0=x$, $x\wedge 1=x$

$-$ gives a complement:  $x\wedge -x=0$, $x\vee -x=1$

$\vee,\wedge$ are associative:  $x\vee (y\vee z)=(x\vee y)\vee z$, $x\wedge (y\wedge z)=(x\wedge y)\wedge z$

$\vee,\wedge$ are commutative:  $x\vee y=y\vee x$, $x\wedge y=y\wedge x$

$\vee,\wedge$ are mutually distributive:  $x\wedge (y\vee z)=(x\wedge y)\vee (x\wedge z)$, $x\vee (y\wedge z)=(x\vee y)\wedge (x\vee z)$

====Definition====
A \emph{Boolean algebra} is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,-\rangle $ of type $\langle 2,0,2,0,1\rangle $
such that

$\langle A,\vee ,0,\wedge ,1\rangle $ is a 
[[bounded distributive lattice]]

$-$ gives a complement:  $x\wedge -x=0$, $x\vee -x=1$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Boolean algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(-x)=-h(x)$

It follows that $h(x\wedge y)=h(x)\wedge h(y)$, $h(0)=0$, $h(1)=1$.

====Definition====
A \emph{Boolean ring} is a structure $\mathbf{A}=\langle A,+
,0,\cdot ,1\rangle $ of type $\langle 2,0,2,0\rangle $
such that

$\langle A,+ ,0,\cdot ,1\rangle $ is a [[commutative ring with unit]]

$\cdot$ is idempotent:  $x\cdot x=x$

Remark: 
The term-equivalence with Boolean algebras is given by $x\wedge y=x\cdot y$, $-x=x+1$, $x\vee y=-(-x\wedge -y)$ and 
$x+y=(x\vee y)\wedge -(x\wedge y)$.

====Definition====
A \emph{Boolean algebra} is a [[Heyting algebra]] $\mathbf{A}=\langle
A,\vee ,0,\wedge ,1,\to\rangle $ such that

$\to 0$ is an involution:  $(x\to 0)\to 0=x$

====Examples====
Example 1: $\langle \mathcal P(S), \cup ,\emptyset, \cap, S, -\rangle$, the
collection of subsets of a sets $S$, with union, intersection, and
setcomplementation.


====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable in NPTIME |
^[[Quasiequational theory]]  |decidable |
^[[First-order theory]]  |decidable |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence regular]]  |yes |
^[[Congruence uniform]]  |yes |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  |yes |
^[[Equationally def. pr. cong.]]  |yes |
^[[Amalgamation property]]  |yes |
^[[Strong amalgamation property]]  |yes |
^[[Epimorphisms are surjective]]  |yes |
^[[Locally finite]]  |yes |
^[[Residual size]]  |2 |

====Finite members====
Number of algebras $=\{ 
\begin{array}{cc}
1 & \text{if size}=2^{n} \\ 
0 & \text{otherwise}\end{array}. $


====Subclasses====
[[One-element algebras]] 

[[Complete Boolean algebras]] 


====Superclasses====
[[Bounded distributive lattices]] 

[[Generalized Boolean algebras]] 

[[Heyting algebras]] 


====References====
