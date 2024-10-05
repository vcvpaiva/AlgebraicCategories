=====Commutative BCK-algebras=====

Abbreviation: **ComBCK**
====Definition====
A \emph{commutative BCK-algebra} is a structure $\mathbf{A}=\langle A,\cdot ,0\rangle$ of type $\langle 2,0\rangle$ such that


(1):  $((x\cdot y)\cdot (x\cdot z))\cdot (z\cdot y) = 0$


(2):  $x\cdot 0 = x$


(3):  $0\cdot x = 0$


(4):  $x\cdot y=y\cdot x= 0 \Longrightarrow x=y$


(5):  $x\cdot (x\cdot y) = y\cdot (y\cdot x)$

Remark: 
Note that the commutativity does not refer to the operation $\cdot$, but rather to the
term operation $x\wedge y=x\cdot (x\cdot y)$, which turns out to be a meet with respect
to the following partial order:

$x\le y \iff x\cdot y=0$, with $0$ as least element.

====Definition====
A \emph{commutative BCK-algebra} is a [[BCK-algebra]] 
$\mathbf{A}=\langle A,\cdot ,0\rangle$ such that

$x\cdot (x\cdot y) = y\cdot (y\cdot x)$

====Definition====
A \emph{commutative BCK-algebra} is a structure $\mathbf{A}=\langle A,\cdot ,0\rangle$ of type $\langle 2,0\rangle$ such that

(1):  $(x\cdot y)\cdot z = (x\cdot z)\cdot y$

(2):  $x\cdot (x\cdot y) = y\cdot (y\cdot x)$

(3):  $x\cdot x = 0$

(4):  $x\cdot 0 = x$

This definition shows that commutative BCK algebras form a variety.

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be commutative BCK-algebras. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\cdot y)=h(x)\cdot h(y) \mbox{ and } h(0)=0$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]                        |variety |
^[[Equational theory]]                | |
^[[Quasiequational theory]]           | |
^[[First-order theory]]               | |
^[[Locally finite]]                   |no |
^[[Residual size]]                    |unbounded |
^[[Congruence distributive]]          |yes |
^[[Congruence modular]]               |yes |
^[[Congruence n-permutable]]          |yes, $n=3$ |
^[[Congruence regular]]               | |
^[[Congruence uniform]]               | |
^[[Congruence extension property]]    | |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]      |no |
^[[Amalgamation property]]            | |
^[[Strong amalgamation property]]     | |
^[[Epimorphisms are surjective]]      | |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &2\\
f(4)= &5\\
f(5)= &11\\
f(6)= &28\\
f(7)= &72\\
f(8)= &192\\
\end{array}$

====Subclasses====
[[Tarski algebras]]

[[MV-algebras]]

====Superclasses====
[[BCK-algebras]] 


====References====

[(Ln19xx>
)]





