=====Hoops=====

====Definition====
A \emph{hoop} is a structure $\mathbf{A}=\langle A,\cdot,\rightarrow,1\rangle $ of type $\langle 2,2,0\rangle$ such that

$\langle A,\cdot ,1\rangle $ is a [[commutative monoid]]

$x\rightarrow ( y\rightarrow z) = (x\cdot y)\rightarrow z$

$x\rightarrow x=1$

$(x\rightarrow y)\cdot x = (y\rightarrow x)\cdot y$


Remark: 
This definition shows that hoops form a variety.

Hoops are partially ordered by the relation $x\leq y \iff
x\rightarrow y=1$.

The operation $x\wedge y = (x\rightarrow y)\cdot x$ is a meet with
respect to this order.


====Definition====
A \emph{hoop} is a structure $\mathbf{A}=\langle A,\cdot,\rightarrow,1\rangle $ of type $\langle 2,2,0\rangle$ such that

$x\cdot y = y\cdot x$

$x\cdot 1 = x$

$x\rightarrow ( y\rightarrow z) = (x\cdot y)\rightarrow z$

$x\rightarrow x=1$

$(x\rightarrow y)\cdot x = (y\rightarrow x)\cdot y$


====Definition====
A \emph{hoop} is a structure $\mathbf{A}=\langle A,\cdot,\rightarrow,1\rangle $ of type $\langle 2,2,0\rangle$ such that

$\langle A,\cdot ,1\rangle $ is a [[commutative monoid]]

and if $x\le y$ is defined by $x\rightarrow y = 1$ then

$\le$ is a partial order,

$\rightarrow$ is the residual of $\cdot$, i.e., $\ x\cdot y\le z \iff y\le x\rightarrow z$, and

$(x\rightarrow y)\cdot x = (y\rightarrow x)\cdot y$.


==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be hoops. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\cdot y)=h(x)\cdot h(y)$, $h(x\rightarrow y)=h(x)\rightarrow h(y) $, $h(1)=1$

====Examples====
Example 1: 

====Basic results====

Finite hoops are the same as [[generalized BL-algebras]] (= divisible residuated lattices) since the join always exists in a finite meet-semilattice with top, and since all finite GBL-algebras are commutative and integral.

====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
^[[Quasiequational theory]]  |decidable |
^[[First-order theory]]  | |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  | |
^[[Congruence regular]]  | |
^[[Congruence uniform]]  | |
^[[Congruence extension property]]  | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &2\\
f(4)= &5\\
f(5)= &10\\
f(6)= &23\\
f(7)= &49\\
\end{array}$

====Subclasses====
[[Wajsberg hoops]] 

[[Idempotent hoops]] 

[[Commutative generalized BL-algebras]] 

====Superclasses====
[[Pocrims]] 

[[Generalized hoops]] 


====References====

[(Ln19xx>
)]