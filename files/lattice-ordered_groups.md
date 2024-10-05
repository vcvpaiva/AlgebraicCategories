=====Lattice-ordered groups=====

Abbreviation: **LGrp**


====Definition====
A \emph{lattice-ordered group} (or $\ell $\emph{-group}) is a structure $\mathbf{L}=\langle L, \vee, \wedge, \cdot, ^{-1}, e\rangle$ such that 

$\langle L, \vee, \wedge\rangle$ is a [[lattice]]

$\langle L, \cdot, ^{-1}, e\rangle$ is a [[group]]

$\cdot$ is order-preserving:  $x\leq y\Longrightarrow uxv\leq uyv$

Remark: 
$xy=x\cdot y$, $x\leq y\Longleftrightarrow x\wedge y=x$ and $x\leq y\Longleftrightarrow x\vee y=y$


====Definition====
A \emph{lattice-ordered group} (or $\ell $\emph{-group}) is a structure $\mathbf{L}=\langle L,\vee ,\cdot ,^{-1},e\rangle $ such that

$\langle L,\vee\rangle $ is a [[semilattice]]

$\langle L,\cdot,^{-1},e\rangle $ is a [[group]]

$\cdot$ is join-preserving:  $u(x\vee y)v=uxv\vee uyv$

Remark: $x\wedge y=( x^{-1}\vee y^{-1}) ^{-1}$


====Definition====
A \emph{lattice-ordered group} (or $\ell $\emph{-group}) is a residuated
lattice $\mathbf{L}=\langle L,\vee ,\wedge ,\cdot ,\backslash
,/,e\rangle $ that satisfies the identity $x(e/x)=e$.

Remark: $x^{-1}=e/x=x\backslash e$, $x/y=xy^{-1}$ and $x\backslash y=x^{-1}y$

==Morphisms==
Let $\mathbf{L}$ and $\mathbf{M}$ be $\ell $-groups. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $f:L\to M$ that is a
homomorphism: $f(x\vee y)=f(x)\vee f(y)$, $f(x\wedge y)=f(x)\wedge f(y)$, $f(x\cdot y)=f(x)\cdot f(y)$, $f(x^{-1})=f(x)^{-1}$, and $f(e)=e$.


====Examples====
$\langle Aut(\mathbf{C}),\mbox{max},\mbox{min},\circ,^{-1},id_{\mathbf{C}}\rangle$, 
the group of order-automorphisms of a [[Chains]] $\mathbf{C}$, with $\mbox{max}$ and $\mbox{min}$ 
(applied pointwise), composition, inverse, and identity automorphism.


====Basic results====
The lattice reducts of lattice-ordered groups are [[distributive lattices]].


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable[(HollandMcCleary1979)] |
^[[Quasiequational theory]]  |undecidable[(GlassGurevich1983)] |
^[[First-order theory]]  |hereditarily undecidable[(Gurevic1967)] [(Burris1985)] |
^[[Congruence distributive]]  |yes, see [[lattices]] |
^[[Congruence extension property]]  | |
^[[Congruence n-permutable]]  |yes, $n=2$, see [[groups]] |
^[[Congruence regular]]  |yes, see [[groups]] |
^[[Congruence uniform]]  |yes, see [[groups]] |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Amalgamation property]]  |no |
^[[Strong amalgamation property]]  |no |
^[[Epimorphisms are surjective]]  | |

====Finite nontrivial members====

None 

====Subclasses====
[[Normal valued lattice-ordered groups]] 

====Superclasses====
[[Cancellative residuated lattices]] 


====References====
[(Burris1985>
Stanley Burris, \emph{A simple proof of the hereditary undecidability of the theory of lattice-ordered abelian groups},
Algebra Universalis,
\textbf{20}, 1985, 400--401, http://www.math.uwaterloo.ca/~snburris/htdocs/MYWORKS/PAPERS/HerUndecLOAG.pdf)]

[(GlassGurevich1983>
A. M. W. Glass, Yuri Gurevich,
\emph{The word problem for lattice-ordered groups},
Trans. Amer. Math. Soc., \textbf{280} 1983, 127--138
[[http://www.ams.org/mathscinet-getitem?mr=85d:06015|MRreview]][[http://www.emis.de/MATH-item?0586.03037|ZMATH]])]

[(Gurevic1967>
Yuri Gurevic, \emph{Hereditary undecidability of a class of lattice-ordered Abelian groups},
Algebra i Logika Sem.,
\textbf{6}, 1967, 45--62)]

[(HollandMcCleary1979>
W. Charles Holland, Stephen H. McCleary,
\emph{Solvability of the word problem in free lattice-ordered groups},
Houston J. Math., \textbf{5} 1979, 99--105
[[http://www.ams.org/mathscinet-getitem?mr=80f:06018|MRreview]][[http://www.emis.de/MATH-item?0404.06009|ZMATH]]
[http://www.chapman.edu/~jipsen/lgroups/lgroupDecisionProc.html implementation])]

[(Pierce1972>
Keith R. Pierce,
\emph{Amalgamations of lattice ordered groups},
Trans. Amer. Math. Soc., \textbf{172} 1972, 249--260
[[http://www.ams.org/mathscinet-getitem?mr=48 :3835|MRreview]][[http://www.emis.de/MATH-item?0259.06017|ZMATH]])]
