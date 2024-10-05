=====Brouwerian semilattices=====

Abbreviation: **BrSlat**

====Definition====
A \emph{Brouwerian semilattice} is a structure $\mathbf{A}=\langle A, \wedge, 1, \rightarrow\rangle$ such that

$\langle A, \wedge, 1\rangle$ is a [[semilattice with identity]]

$\rightarrow$ gives the residual of $\wedge$:  $x\wedge y\leq z\Longleftrightarrow y\leq x\rightarrow z$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Brouwerian semilattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\wedge y)=h(x)\wedge h(y)$, $h(1)=1$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$

====Definition====
A \emph{Brouwerian semilattice} is a [[hoop]] $\mathbf{A}=\langle A, \cdot, 1, \rightarrow\rangle$ such that

$\cdot$ is idempotent:  $x\cdot x=x$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  | |
^[[Locally finite]]  |yes |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence e-regular]]  |yes, $e=1$ |
^[[Congruence uniform]]  | |
^[[Congruence extension property]]  | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |

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

Values known up to size 49 [(ErneHeitzigReinhold2002)]


====Subclasses====
[[Brouwerian algebras]] 


====Superclasses====
[[Semilattices with identity]] 

[[Hoops]] 


====References====

[(ErneHeitzigReinhold2002>
M. Ern\'e, J. Heitzig, J. Reinhold,
\emph{On the number of distributive lattices}, 
Electronic J. Combinatorics 9 (2002), no. 1, Research Paper 24, 23 pp.
)]