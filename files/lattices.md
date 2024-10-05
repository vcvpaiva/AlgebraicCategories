=====Lattices=====

Abbreviation: **Lat**


====Definition====
A \emph{lattice} is a structure $\mathbf{L}=\langle L,\vee ,\wedge
\rangle $, where $\vee $ and $\wedge $ are infix binary operations
called the \emph{join} and \emph{meet}, such that

$\vee ,\wedge $ are associative:  $(x\vee y)\vee z=x\vee (y\vee z)$, $(x\wedge y)\wedge z=x\wedge (y\wedge z)$

$\vee ,\wedge $ are commutative:  $x\vee y=y\vee x$, $x\wedge y=y\wedge x$

$\vee ,\wedge $ are absorbtive:  $(x\vee y)\wedge x=x$, $(x\wedge y)\vee x=x$.

Remark: 
It follows that $\vee $ and $\wedge $ are idempotent: $x\vee x=x$, $x\wedge x=x$.

This definition shows that lattices form a variety.

A partial order $\leq $ is definable in any lattice by 
$x\leq y\Longleftrightarrow x\wedge y=x$, or equivalently by 
$x\leq y\Longleftrightarrow x\vee y=y$.

==Morphisms==
Let $\mathbf{L}$ and $\mathbf{M}$ be lattices. A morphism from $\mathbf{L}$
to $\mathbf{M}$ is a function $h:L\to M$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$


====Definition====
A \emph{lattice} is a structure $\mathbf{L}=\langle L,\vee ,\wedge
\rangle $ of type $\langle 2,2\rangle $ such that

$\langle L,\vee \rangle $ and $\langle L,\wedge
\rangle $ are 
[[semilattices]], and

$\vee ,\wedge $ are absorbtive:  $(x\vee y)\wedge x=x$, $(x\wedge y)\vee x=x$


====Definition====
A \emph{lattice} is a structure $\mathbf{L}=\langle L,\leq
\rangle $ that is a 
[[partially ordered set]] in which all elements $x,y\in L$ have a

least upper bound:  $z=x\vee y\Longleftrightarrow x\leq z$, $y\leq z\ \mbox{and}\ \forall w\ (x\leq w$, $y\leq w\Longrightarrow z\leq w)$ and a

greatest lower bound:  $z=x\wedge y\Longleftrightarrow z\leq x$, $z\leq y\ \mbox{and}\ \forall w\ (w\leq x$, $w\leq y\Longrightarrow w\leq z)$


====Definition====
A \emph{lattice} is a structure $\mathbf{L}=\langle L,\vee ,\wedge
,\leq \rangle $ such that $\langle L,\leq \rangle $ is a 
[[partially ordered set]] and the following quasiequations hold:

$\vee $-left:  $x\leq z$ and $y\leq z\ \Longrightarrow x\vee y\leq z$

$\vee $-right:  $z\leq x\Longrightarrow z\leq x\vee y$, $\quad z\leq y\Longrightarrow z\leq x\vee y$

$\wedge $-right:  $z\leq x$ and $z\leq y\Longrightarrow z\leq x\wedge y$

$\wedge $-left:  $x\leq z\Longrightarrow x\wedge y\leq z$, $\quad y\leq z\Longrightarrow x\wedge y\leq z$

Remark: 
These quasiequations give a cut-free Gentzen system to decide the equational
theory of lattices.


====Examples====
Example 1: $\langle P(S),\cup ,\cap ,\subseteq \rangle $, the collection of
subsets of a sets $S$, ordered by inclusion.

/*[[Lattices (mace)]]*/


====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable in polynomial time |
^[[Quasiequational theory]]  |decidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes [(Nenosuke Funayama,Tadasi Nakayama,\emph{On the distributivity of a lattice of lattice-congruences},
Proc. Imp. Acad. Tokyo,
\textbf{18} 1942, 553--554)] |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |no |
^[[Congruence regular]]  |no |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  |no |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]  |no |
^[[Amalgamation property]]  |yes |
^[[Strong amalgamation property]]  |yes [(Bjarni J\'onsson,\emph{Universal relational systems},
Math. Scand., \textbf{4} 1956, 193--208)] |
^[[Epimorphisms are surjective]]  |yes |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &1\\
f(4)= &2\\
f(5)= &5\\
f(6)= &15\\
f(7)= &53\\
f(8)= &222\\
f(9)= &1078\\
f(10)= &5994\\
f(11)= &37622\\
f(12)= &262776\\
f(13)= &2018305\\
f(14)= &16873364\\
f(15)= &152233518\\
f(16)= &1471613387\\
f(17)= &15150569446\\
f(18)= &165269824761\\
f(19)= &1901910625578
\end{array}$[(Jobst Heitzig, J\"urgen Reinhold, \emph{Counting finite lattices},
Algebra Universalis,
\textbf{48}, 2002, 43--53)][(Peter Jipsen, Nathan Lawless, \emph{Generating all finite modular lattices of a given size}, 
Algebra Universalis, \textbf{74}, 2015, 253--264)]


[[http://math.chapman.edu/~jipsen/posets/lattices77.html|Diagrams of lattices of size 2 to 7]]

/*[[Finite lattices]] of size $\le 7$

[[Subdirectly irreducible lattices]] of size $\le 7$

[[Lattices not in some subclasses]] of size $\le 7$
*/

====Subclasses====
[[Modular lattices]] 

[[Semidistributive lattices]] 

[[Neardistributive lattices]] 

[[Join-complete lattices]] 

[[Meet-complete lattices]] 

====Superclasses====
[[Semilattices]] 

[[Weakly associative lattices]] 


====References====
