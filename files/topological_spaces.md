=====Topological spaces=====

Abbreviation: **Top**

====Definition====
A \emph{topological space} is a structure $\mathbf{X}=\langle X,\tau\rangle$, 
where $\tau=\Omega(\mathbf{X})\subseteq \mathcal P(X)$
is a collection of subsets of $X$ called the \emph{open sets of} $\mathbf{X}$ such that


any union of open sets is open:  $\mathcal{U}\subseteq\Omega(\mathbf{X})\Longrightarrow\bigcup\mathcal{U}\in\Omega(\mathbf{X})$


any finite intersection of open sets is open:  $U,V\in\Omega(\mathbf{X})\Longrightarrow U\cap V\in\Omega(\mathbf{X})$ and $X\in\Omega(\mathbf{X})$

Remark: Note that the union of an empty collection is empty, so $\emptyset\in\Omega(\mathbf{X})$.

The set of \emph{closed sets of} $\mathbf{X}$ is $K(\mathbf{X})=\{X-U\mid U\in\Omega(\mathbf{X})\}$.


==Morphisms==
Let $\mathbf{X}$ and $\mathbf{Y}$ be topological spaces. 
A morphism from $\mathbf{X}$ to $\mathbf{Y}$ is a function $f:X\rightarrow Y$ that is \emph{continuous}: 

$V\in\Omega(\mathbf{Y})\Longrightarrow f^{-1}[V]\in\Omega(\mathbf{X})$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |second-order |
^[[Amalgamation property]]  |yes |
^[[Strong amalgamation property]]  |yes |
^[[Epimorphisms are surjective]]  |yes |

Remark: 
The properties given above use an $(\mathcal{E},\mathcal{M})$ factorization system with $\mathcal{E}=$ surjective morphisms and
$\mathcal{M}=$ embeddings.


====Subclasses====
[[T0-spaces]] 


====Superclasses====
[[Sets]] 


====References====
