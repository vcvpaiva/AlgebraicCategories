=====BCK-join-semilattices=====

Abbreviation: **BCKJSlat**
====Definition====
A \emph{BCK-join-semilattice} is a structure $\mathbf{A}=\langle A,\vee,\rightarrow,1\rangle$ of type $\langle 2,2,0\rangle$ such that

(1):  $(x\rightarrow y)\rightarrow ((y\rightarrow z)\rightarrow (x\rightarrow z)) = 1$

(2):  $1\rightarrow x = x$

(3):  $x\rightarrow 1 = 1$

(4):  $x\rightarrow (x\vee y) = 1$

(5):  $x\vee((x\rightarrow y)\rightarrow y) = ((x\rightarrow y)\rightarrow y)$

$\vee$ is idempotent:  $x\vee x = x$

$\vee$ is commutative:  $x\vee y = y\vee x$

$\vee$ is associative:  $(x\vee y)\vee z = x\vee (y\vee z)$

Remark: 
$x\le y \iff x\rightarrow y=1$ is a partial order, with $1$ as greatest element, and $\vee$ is a join
for this order. [(Idziak1984)]

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be BCK-join-semilattices. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\rightarrow y)=h(x)\rightarrow h(y)$ and $h(1)=1$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]                        |variety |
^[[Equational theory]]                | |
^[[Quasiequational theory]]           | |
^[[First-order theory]]               | |
^[[Locally finite]]                   | |
^[[Residual size]]                    | |
^[[Congruence distributive]]          | |
^[[Congruence modular]]               | |
^[[Congruence n-permutable]]          | |
^[[Congruence regular]]               | |
^[[Congruence uniform]]               | |
^[[Congruence extension property]]    | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]      | |
^[[Amalgamation property]]            | |
^[[Strong amalgamation property]]     | |
^[[Epimorphisms are surjective]]      | |
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
[[BCK-lattices]] 

====Superclasses====
[[BCK-algebras]] 


====References====

[(Idziak1984>
Pawel M. Idziak, \emph{Lattice operation in BCK-algebras},
Math. Japon., \textbf{29}, 1984, 839--846 [[MRreview]]
)]\end{document}
%</pre>
