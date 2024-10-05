=====Relation algebras=====

Abbreviation: **RA**
====Definition====
A \emph{relation algebra} is a structure $\mathbf{A}=\langle A,\vee,0,\wedge,1,\neg,\circ,^{\smile},e\rangle$ such that

$\langle A,\vee,0,\wedge,1,\neg\rangle$ is a [[Boolean algebra]]

$\langle A,\circ,e\rangle $ is a [[monoid]]

$\circ$ is \emph{join-preserving}: $(x\vee y)\circ z=(x\circ z)\vee (y\circ z)$

$^{\smile}$ is an \emph{involution}: $x^{\smile\smile}=x$, $(x\circ y)^{\smile}=y^{\smile}\circ x^{\smile}$

$^{\smile}$ is \emph{join-preserving}: $(x\vee y)^{\smile}=x^{\smile}\vee y^{\smile}$

$\circ$ is residuated: $x^{\smile}\circ(\neg (x\circ y))\le\neg y$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be relation algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a Boolean homomorphism and preserves $\circ$, $^{\smile}$, $e$:

$h(x\circ y)=h(x)\circ h(y)$, $h(x^{\smile})=h(x)^{\smile}$, $h(e)=e$

====Examples====
Example 1: $\langle \mathcal P(U^2), \cup, \emptyset, \cap, U^2, -, \circ, ^\smile, id_U \rangle$ the full relation algebra of binary relations on a set $U$.

Example 2: $\langle \mathcal P(G), \cup, \emptyset, \cap, G, -, \circ, ^\smile, \{e\} \rangle$ the group relation algebra of a [[group]] $\langle G, *, ^{-1}, e \rangle$, where $X\circ Y=\{x*y : x\in X, y\in Y\}$ and $X^\smile=\{x^{-1} : x\in X\}$.

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
^[[Discriminator variety]]  |yes |
^[[Amalgamation property]]  |no |
^[[Strong amalgamation property]]  |no |
^[[Epimorphisms are surjective]]  |no |


====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &0\\
f(4)= &3\\
f(5)= &0\\
f(6)= &0\\
\end{array}$

[[http://www.chapman.edu/~jipsen/gap/ramaddux.html|Small relation algebras]]


====Subclasses====
[[n-dimensional relation algebras]] 

[[Representable relation algebras]] 

[[Commutative relation algebras]] 

[[Square-increasing relation algebras]] 


====Superclasses====
[[Sequential algebras]] 

[[Semiassociative relation algebras]] 


====References====

/*[(Ln19xx> )]*/
