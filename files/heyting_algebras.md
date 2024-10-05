=====Heyting algebras=====

Abbreviation: **HA**


====Definition====
A \emph{Heyting algebra} is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\to \rangle $ such that


$\langle A,\vee ,0,\wedge ,1\rangle $ is a bounded distributive
lattice


$\to$ gives the residual of $\wedge$:  $x\wedge y\leq z\Longleftrightarrow y\leq x\to z$

====Definition====
A \emph{Heyting algebra} is a FLew-algebra $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\cdot ,\to \rangle $ such that


$x\wedge y=x\cdot y$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Heyting algebras. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\to B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(0)=0$, 
$h(x\wedge y)=h(x)\wedge h(y)$, $h(1)=1$, 
$h(x\to y)=h(x)\to h(y)$

====Examples====
Example 1: The open sets of any [[topological space]] $\mathbf X$ form a Heyting algebra under the operations of union $\cup$, 
empty set $\emptyset$, intersection $\cap$, whole space $X$, and the operation $U\to V=$ interior of $(X - U)\cup V$.

Example 2: Any [[frame]] can be expanded to a unique Heyting algebra by defining $x\to y = \bigvee\{z:x\wedge z\le y\}$.

====Basic results====
Any finite distributive lattice is the reduct of a unique Heyting algebra. More generally the same result holds for any complete and completely distributive lattice.

A Heyting algebra is subdirectly irreducible if and only if it has a unique coatom.

====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
^[[Quasiequational theory]]  |decidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence e-regular]]  |yes, $e=1$ |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  |yes |
^[[Equationally def. pr. cong.]]  |yes |
^[[Amalgamation property]]  |yes |
^[[Strong amalgamation property]]  |yes |
^[[Epimorphisms are surjective]]  |yes |
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

Values known up to size 49 [(EHR2002> Marcel Ern\'e;, Jobst Heitzig and J\"urgen Reinhold,\emph{On the number of distributive lattices},
Electron. J. Combin.,
\textbf{9}2002,Research Paper 24, 23 pp. (electronic)[[MRreview]])]

====Subclasses====
[[Goedel algebras]] 

====Superclasses====
[[Bounded distributive lattices]] 


====References====

[(Ln19xx>
)]