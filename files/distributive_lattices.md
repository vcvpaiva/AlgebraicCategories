=====Distributive lattices=====

Abbreviation: **DLat**
====Definition====
A \emph{distributive lattice} is a lattice $\mathbf{L}=\langle L,\vee
,\wedge\rangle $ such that

$\wedge $ distributes over $\vee $:  $x\wedge (y\vee z) = (x\wedge y) \vee (x\wedge z)$

====Definition====
A \emph{distributive lattice} is a lattice $\mathbf{L}=\langle L,\vee
,\wedge\rangle $ such that

$\vee $ distributes over $\wedge $:  $x\vee (y\wedge z) = (x\vee y) \wedge (x\vee z)$

====Definition====
A \emph{distributive lattice} is a lattice $\mathbf{L}=\langle L,\vee
,\wedge \rangle $ such that

$(x\wedge y) \vee (x\wedge z) \vee (y\wedge z) = (x\vee y) \wedge (x\vee z) \wedge (y\vee z)$

====Definition====
A \emph{distributive lattice} is a lattice $\mathbf{L}=\langle L,\vee
,\wedge \rangle $ such that $\mathbf{L}$ has no sublattice isomorphic
to the diamond $\mathbf{M}_{3}$ or the pentagon $\mathbf{N}_{5}$

====Definition====
A \emph{distributive lattice} is a structure $\mathbf{L}=\langle L,\vee ,\wedge
\rangle $ of type $\langle 2,2\rangle $ such that

$x\wedge(x\vee y)=x$ and

$x\wedge(y\vee z)=(z\wedge x)\vee(y\wedge x)$.[(Sholander1951)] 


==Morphisms==
Let $\mathbf{L}$ and $\mathbf{M}$ be distributive lattices. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\to M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$

====Examples====
Example 1: $\langle P(S),\cup ,\cap ,\subseteq \rangle $, the collection of
subsets of a sets $S$, ordered by inclusion.


====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
^[[Quasiequational theory]]  |decidable |
^[[First-order theory]]  |undecidable |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |no |
^[[Congruence regular]]  |no |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  |no |
Equationally def. pr. cong. & yes, $\begin{array}{c}\langle c,d\rangle\in \text{Cg}(a,b)\iff \\
(a\wedge b)\wedge c=(a\wedge b)\wedge d\\ (a\vee b)\vee c=(a\vee b)\vee d\end{array}$\\\hline
^[[Amalgamation property]]  |yes |
^[[Strong amalgamation property]]  |no |
^[[Epimorphisms are surjective]]  |no |
^[[Locally finite]]  |yes |
^[[Residual size]]  |2 |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &3\\
f(6)= &5\\
f(7)= &8\\
f(8)= &15\\
f(9)= &26\\
f(10)= &47\\
f(11)= &82\\
f(12)= &151\\
f(13)= &269\\
f(14)= &494\\
f(15)= &891\\
f(16)= &1639\\
f(17)= &2978\\
f(18)= &5483\\
f(19)= &10006\\
f(20)= &18428\\
\end{array}$

Values known up to size 49 [(ErneHeitigReinhold2002)]

====Subclasses====
[[One-element algebras]] 

[[Bounded distributive lattices]] 

[[Complete distributive lattices]] 

====Superclasses====
[[Modular lattices]] 

[[Semidistributive lattices]] 


====References====

[(ErneHeitigReinhold2002>
M. Ern\'e, J. Heitzig, J. Reinhold,
\emph{On the number of distributive lattices},
Electronic J. Combinatorics 9 (2002), no. 1, Research Paper 24, 23 pp.
)]

[(Sholander1951>
M. Sholander, 
\emph{Postulates for distributive lattices}. 
Canadian J. Math. 3, (1951). 28–30.
)]