=====Normal valued lattice-ordered groups=====

Abbreviation: **NVLGrp**


====Definition====
A \emph{normal valued lattice-ordered group} (or \emph{normal valued} $\ell$\emph{-group}) is a 
[[lattice-ordered group]]
$\mathbf{L}=\langle L, \vee, \wedge, \cdot, ^{-1}, e\rangle$ that satisfies

$(x\vee x^{-1})(y\vee y^{-1}) \le (y\vee y^{-1})^2(x\vee x^{-1})^2$

==Morphisms==
Let $\mathbf{L}$ and $\mathbf{M}$ be $\ell$-groups. A morphism from $\mathbf{L}$ to $\mathbf{M}$ is a function $f:L\rightarrow M$ that is a
homomorphism: $f(x\vee y)=f(x)\vee f(y)$ and $f(x\cdot y)=f(x)\cdot f(y)$.

Remark: It follows that $f(x\wedge y)=f(x)\wedge f(y)$, $f(x^{-1})=f(x)^{-1}$, and $f(e)=e$


====Examples====


====Basic results====
The variety of normal valued $\ell$-groups is the largest proper subvariety of [[lattice-ordered groups]] [(Holland1976)].


====Properties====
^[[Classtype]]                       |variety |
^[[Equational theory]]               | |
^[[Quasiequational theory]]          | |
^[[First-order theory]]              |hereditarily undecidable [(Gurevic1967)] [(Burris1985)] |
^[[Locally finite]]                  |no |
^[[Residual size]]                   | |
^[[Congruence distributive]]         |yes (see [[lattices]]) |
^[[Congruence modular]]              |yes |
^[[Congruence n-permutable]]         |yes, $n=2$ (see [[groups]]) |
^[[Congruence regular]]              |yes, (see [[groups]]) |
^[[Congruence uniform]]              |yes, (see [[groups]]) |
^[[Congruence extension property]]   | |
^[[Definable principal congruences]] | |
^[[Equationally def. pr. cong.]]     | |
^[[Amalgamation property]]           | |
^[[Strong amalgamation property]]    | |
^[[Epimorphisms are surjective]]     | |


====Finite nontrivial members====
None


====Subclasses====
[[Representable lattice-ordered groups]] 


====Superclasses====
[[Lattice-ordered groups]] 


====References====
[(Burris1985>
Stanley Burris, \emph{A simple proof of the hereditary undecidability of the theory of lattice-ordered abelian groups},
Algebra Universalis,
\textbf{20}, 1985, 400--401, http://www.math.uwaterloo.ca/~snburris/htdocs/MYWORKS/PAPERS/HerUndecLOAG.pdf)]

[(Gurevic1967>
Yuri Gurevic, \emph{Hereditary undecidability of a class of lattice-ordered Abelian groups},
Algebra i Logika Sem.,
\textbf{6}, 1967, 45--62)]

[(Holland1976>
W. Charles Holland, \emph{The largest proper variety of lattice-ordered groups},
Proceedings of the AMS, \textbf{57}(1), 1976, 25--28)]