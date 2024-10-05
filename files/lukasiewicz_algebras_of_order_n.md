=====Lukasiewicz algebras of order n=====

Abbreviation: **LA$_n$**
====Definition====
A \emph{Lukasiewicz algebra of order $n$} is a structure $\mathbf{A}=\langle A,\vee
,0,\wedge ,1,\neg,\sigma_0,\ldots,\sigma_{n-1}\rangle $ such that


$\langle A,\vee ,0,\wedge ,1, \neg\rangle $ is a [[De Morgan algebras]]


1. 
$\sigma_i$ is a lattice homomorphism:  $\sigma_i(x\vee y)=\sigma_i(x)\vee\sigma_i(y)
\mbox{and} \sigma_i(x\wedge y)=\sigma_i(x)\wedge\sigma_i(y)$

2. 
$\sigma_i(x) \vee \neg(\sigma_i(x)) = 1$, $\sigma_i(x) \wedge \neg(\sigma_i(x)) = 0$

3. 
$\sigma_i(\sigma_j(x)) = \sigma_j(x)$ for $1 \le j \le n-1$

4. 
$\sigma_i(\neg x) = \neg(\sigma_{n-i}(x))$

5. 
$\sigma_i(x) \wedge \sigma_j(x) = \sigma_i(x)$ for $i \le j \le n - 1$

6. 
$x \vee \sigma_{n-1}(x) = \sigma_{n-1}(x)$, $x \wedge \sigma_1(x) = \sigma_1(x)$

7. 
$y \wedge (x \vee \neg(\sigma_i(x)) \vee \sigma_{i+1}(y)) = y$ for $i \ne n - 1$

==Morphisms==
Let $\mathbf{A}$ and $\mathbf{B}$ be Lukasiewicz algebras of order $n$. A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a
homomorphism: 

$h(x\vee y)=h(x)\vee h(y)$, $h(\neg x)=\neg h(x)$, $h(\sigma_i(x))=\sigma_i(h(x))$ for $i=0,\ldots,n-1$

====Examples====
Example 1: 

====Basic results====

====Properties====
^[[Classtype]]  |Variety |
^[[Equational theory]]  |decidable |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  | |
^[[Congruence distributive]]  |Yes |
^[[Congruence modular]]  |Yes |
^[[Congruence n-permutable]]  | |
^[[Congruence regular]]  | |
^[[Congruence uniform]]  | |
^[[Congruence extension property]]  | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  | |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |
^[[Locally finite]]  |yes |
^[[Residual size]]  |$n$ |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &\\
f(3)= &\\
f(4)= &\\
f(5)= &\\
f(6)= &\\
f(7)= &\\
f(8)= &\\
f(9)= &\\
f(10)= &\\
\end{array}$

====Subclasses====
[[Boolean algebras]] 

====Superclasses====
[[De Morgan algebras]] 


====References====

[(Ln19xx>
)]