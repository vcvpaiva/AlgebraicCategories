=====Basic logic algebras=====

Abbreviation: **BLA**

====Definition====
A \emph{basic logic algebra} or \emph{BL-algebra} is a structure $\mathbf{A}=\langle A,\vee ,0,\wedge ,1,\cdot ,\to \rangle $ such that

$\langle A,\vee ,0,\wedge ,1\rangle $ is a 
[[bounded lattice]]

$\langle A,\cdot ,1\rangle $ is a [[commutative monoid]]

$\to$ gives the residual of $\cdot $:  $x\cdot y\leq z\Longleftrightarrow y\leq x\to z$

prelinearity:  $( x\to y) \vee ( y\to x) =1$

BL:  $x\cdot(x\to y)=x\wedge y$

Remark: 
The BL identity implies that the lattice is distributive.

====Definition====
A \emph{basic logic algebra} is a [[FLe-algebra]] $\mathbf{A}=\langle
A,\vee ,0,\wedge ,1,\cdot ,\to \rangle $ such that

linearity:  $( x\to y) \vee ( y\to x) =1$

BL:  $x\cdot (x\to y)=x\wedge y$

Remark: 
The BL identity implies that the identity element $1$ is the top of the lattice.

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be basic logic algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(1)=1$, $h(x\wedge
y)=h(x)\wedge h(y)$, $h(0)=0$, $h(x\cdot
y)=h(x)\cdot h(y)$, $h(x\to y)=h(x)\to h(y)$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  | |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence e-regular]]  |yes, $e=1$ |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  |no |
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
f(8)= &111\\
\end{array}$

The number of subdirectly irreducible BL-algebras of size $n$ is $2^{n-2}$.


====Subclasses====
[[MV-algebras]] 

[[Heyting algebras]] 


====Superclasses====
[[Generalized basic logic algebras]] 

[[FLew-algebras]] 


====References====

