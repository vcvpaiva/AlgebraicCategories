=====Bounded distributive lattices=====

Abbreviation: **BDLat**

====Definition====
A \emph{bounded distributive lattice} is a structure $\mathbf{L}=\langle L,\vee ,0,\wedge ,1\rangle $ such that

$\langle L,\vee ,\wedge \rangle $ is a 
[[distributive lattice]]

$0$ is the least element:  $0\leq x$

$1$ is the greatest element:  $x\leq 1$

==Morphisms==
Let $\mathbf{L}$ and $\mathbf{M}$ be bounded distributive lattices. A morphism from 
$\mathbf{L}$ to $\mathbf{M}$ is a function $h:L\to M$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$, $h(0)=0$, $h(1)=1$

====Examples====
Example 1: $\langle \mathcal P(S), \cup, \emptyset, \cap, S\rangle$, the collection
of subsets of a set $S$, with union, empty set, intersection, and the whole
set $S$.



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
^[[Equationally def. pr. cong.]]  |no |
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
\end{array}$     
$\begin{array}{lr}
f(6)= &5\\
f(7)= &8\\
f(8)= &15\\
f(9)= &26\\
f(10)= &47\\
\end{array}$     
$\begin{array}{lr}
f(11)= &82\\
f(12)= &151\\
f(13)= &269\\
f(14)= &494\\
f(15)= &891\\
\end{array}$     
$\begin{array}{lr}
f(16)= &1639\\
f(17)= &2978\\
f(18)= &5483\\
f(19)= &10006\\
f(20)= &18428\\
\end{array}$

Values known up to size 49 [(EHR2002)].

====Subclasses====
[[Boolean algebras]] 

[[Complete distributive lattices]] 

====Superclasses====
[[Distributive lattices]] 

[[Bounded modular lattices]] 


====References====

[(EHR2002>
Marcel Erne, Jobst Heitzig and J\"urgen Reinhold, \emph{On the number of distributive lattices}, Electron. J. Combin.,
\textbf{9}, 2002, Research Paper 24, 23 pp. (electronic)
)]