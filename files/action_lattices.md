
=====Action lattices=====


Abbreviation: **ActLat**

====Definition====
An \emph{action lattice} is a structure $\mathbf{A}=\langle A,\vee,\wedge,0,\cdot,1,^*,\backslash ,/\rangle$ 
of type $\langle 2,2,0,2,0,1,2,2\rangle$ such that

$\langle A,\vee,0,\cdot,1,^*\rangle$ is a [[Kleene algebra]]

$\langle A,\vee,\wedge\rangle$ is a [[lattice]]

$\backslash$ is the left residual of $\cdot $:  $y\leq x\backslash z\Longleftrightarrow xy\leq z$

$/$ is the right residual of $\cdot$:  $x\leq z/y\Longleftrightarrow xy\leq z$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be action lattices. A morphism from $\mathbf{A}$ 
to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(x\wedge y)=h(x)\wedge h(y)$,
$h(x\cdot y)=h(x)\cdot h(y)$, $h(x\backslash
y)=h(x)\backslash h(y)$, $h(x/y)=h(x)/h(y)$, $h(x^*)=h(x)^*$, $h(0)=0$, $h(1)=1$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  | |
^[[Quasiequational theory]]  |undecidable |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence regular]]  |no |
^[[Congruence e-regular]]  |yes |
^[[Congruence uniform]]  |no |
^[[Congruence extension property]]  |no |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]  |no |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |

====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &1\\
f(3)= &3\\
f(4)= &20\\
f(5)= &149\\
f(6)= &1488\\
\end{array}$


====Subclasses====
[[Commutative action lattices]] 


====Superclasses====
[[Action algebras]] 

[[Residuated lattices]] 


====References====

[(Kozen1994>
D. Kozen, \emph{On action algebras}, In J. van Eijck and A. Visser, editors,
\emph{Logic and Information Flow}, MIT Press, 1994, 78--88 
see also http://www.cs.cornell.edu/kozen/papers/act.ps
)]