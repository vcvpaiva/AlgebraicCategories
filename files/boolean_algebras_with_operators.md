=====Boolean algebras with operators=====

Abbreviation: **BAO**

====Definition====
A \emph{Boolean algebra with operators} is a structure $\mathbf{A}=\langle A,\vee,0,
\wedge,1,\neg,f_i\ (i\in I)\rangle$ such that

$\langle A,\vee,0,\wedge,1,\neg\rangle$ is a Boolean algebra

$f_i$ is \emph{join-preserving} in each argument:  
$f_i(\ldots,x\vee y,\ldots)=f_i(\ldots,x,\ldots)\vee f_i(\ldots,y,\ldots)$


$f_i$ is \emph{normal} in each argument:  $f_i(\ldots,0,\ldots)=0$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Boolean algebras with operators of the same signature. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a Boolean homomorphism and preserves all the operators:

$h(f_i(x_0,\ldots,x_{n-1}))=f_i(h(x_0),\ldots,h(x_{n-1}))$

====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |variety |
^[[Equational theory]]  |decidable |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  |undecidable |
^[[Locally finite]]  |no |
^[[Residual size]]  |unbounded |
^[[Congruence distributive]]  |yes |
^[[Congruence modular]]  |yes |
^[[Congruence n-permutable]]  |yes, $n=2$ |
^[[Congruence regular]]  |yes |
^[[Congruence uniform]]  |yes |
^[[Congruence extension property]]  |yes |
^[[Definable principal congruences]]  |no |
^[[Equationally def. pr. cong.]]  |no |
^[[Amalgamation property]]  |yes |
^[[Strong amalgamation property]]  |yes |
^[[Epimorphisms are surjective]]  |yes |


====Subclasses====
[[Modal algebras]] 

[[Boolean monoids]] 


====Superclasses====
[[Boolean algebras]] 


====References====

[(Ln19xx>
)]




