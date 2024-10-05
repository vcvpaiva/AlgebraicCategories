=====Sequential algebras=====

Abbreviation: **SeA**
====Definition====
A \emph{sequential algebra} is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,\circ,e,\triangleright,\triangleleft\rangle$ such that


$\langle A,\vee,0,
\wedge,1,\neg\rangle$ is a [[Boolean algebra]]


$\langle A,\circ,e\rangle $ is a [[monoid]]


$\triangleright$ is the \emph{right-conjugate} of $\circ$:  
$(x\circ y)\wedge z=0 \iff (x\triangleright z)\wedge y=0$


$\triangleleft$ is the \emph{left-conjugate} of $\circ$:  
$(x\circ y)\wedge z=0 \iff (z\triangleleft y)\wedge x=0$


$\triangleright,\triangleleft$ are \emph{balanced}:  
$x\triangleright e=e\triangleleft x$


$\circ$ is \emph{euclidean}:  
$x\cdot(y\triangleleft z)\leq (x\cdot y)\triangleleft z$


Remark: 

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be sequential algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a Boolean homomorphism and preserves $\circ$, $\triangleright$, $\triangleleft$, $e$:

$h(x\circ y)=h(x)\circ h(y)$, $h(x\triangleright y)=h(x)\triangleright h(y)$, $h(x\triangleleft y)=h(x)\triangleleft h(y)$, $h(e)=e$
====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |undecidable |
^[[Quasiequational theory]]  |undecidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence regular]]  |yes |
^[[Congruence uniform]]  |yes |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  |yes |
^[[Equationally def. pr. cong.]]  |yes |
^[[Discriminator variety]]  |no |
^[[Amalgamation property]]  |no |
^[[Strong amalgamation property]]  |no |
^[[Epimorphisms are surjective]]  |no |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &\\
f(3)= &\\
f(4)= &\\
f(5)= &\\
f(6)= &\\
\end{array}$

====Subclasses====
[[Relation algebras]] 

[[Representable sequential algebras]] 

====Superclasses====
[[Distributive residuated lattices]] 

[[Semiassociative sequential algebras]] 


====References====

[(Ln19xx>
)]





