=====Nonassociative relation algebras=====

Abbreviation: **NA**
====Definition====
A \emph{nonassociative relation algebra} is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,\circ,^{\smile},e\rangle$ such that


$\langle A,\vee,0,
\wedge,1,\neg\rangle$ is a [[Boolean algebra]]


$e$ is an \emph{identity} for $\circ$:  $x\circ e=x$, $e\circ x=x$


$\circ$ is \emph{join-preserving}:  
$(x\vee y)\circ z=(x\circ z)\vee (y\circ z)$


$^{\smile}$ is an \emph{involution}:  
${x^\smile}^\smile=x$, $(x\circ y)^{\smile} z=y^{\smile}\circ x^{\smile}$


$^{\smile}$ is \emph{join-preserving}:  
$(x\vee y)^{\smile} z=x^{\smile}\vee y^{\smile}$


$\circ$ is residuated:  $x^{\smile}\circ(\neg (x\circ y))\le\neg y$


Remark: 

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be relation algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a Boolean homomorphism and preserves $\circ$, $^{\smile}$, $e$:

$h(x\circ y)=h(x)\circ h(y)$, $h(x^{\smile})=h(x)^{\smile}$, $h(e)=e$
====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
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
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Discriminator variety]]  |no |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |
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
[[Weakly associative relation algebras]] 

====Superclasses====
[[Nonassociative sequential algebras]] 


====References====

[(Ln19xx>
)]





