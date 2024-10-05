=====Inverse semigroups=====

Abbreviation: **InvSgrp**
====Definition====
An \emph{inverse semigroup} is a structure $\mathbf{S}=\langle
S,\cdot,^{-1}\rangle $ such that


$\cdot$ is associative:  $(xy)z=x(yz)$


$^{-1}$ is an inverse:  $xx^{-1}x=x$ and $(x^{-1})^{-1}=x$


idempotents commute:  $xx^{-1}yy^{-1}=yy^{-1}xx^{-1}$
==Morphisms==
Let $\mathbf{S}$ and $\mathbf{T}$ be inverse semigroups. A morphism from 
$\mathbf{S}$ to $\mathbf{T}$ is a function $h:S\rightarrow T$ that is a
homomorphism: 

$h(xy)=h(x)h(y)$, $h(x^{-1})=h(x)^{-1}$

====Examples====
Example 1: $\langle I_X,\circ,^{-1}\rangle$, the \emph{symmetric inverse semigroup} of all one-to-one partial functions on a set $X$, with
composition and function inverse. Every inverse semigroup can be embedded in a symmetric inverse semigroup.


====Basic results====

$x*x=x \implies \exists y\ x=y*y^{-1}$

$\forall x\exists y\ xx^{-1}=y^{-1}y$

====Properties====
^[[Classtype]]  |Variety |
^[[Equational theory]]  | |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  | |
^[[Locally finite]]  |No |
^[[Residual size]]  | |
^[[Congruence distributive]]  |No |
^[[Congruence modular]]  |No |
^[[Congruence n-permutable]]  |No |
^[[Congruence regular]]  |No |
^[[Congruence uniform]]  |No |
^[[Congruence extension property]]  |No |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  |No |
^[[Amalgamation property]]  |Yes |
^[[Strong amalgamation property]]  |Yes |
^[[Epimorphisms are surjective]]  |Yes |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &2\\
f(3)= &5\\
f(4)= &16\\
f(5)= &52\\
f(6)= &208\\
f(7)= &911\\
f(8)= &4637\\
f(9)= &26422\\
f(10)= &169163\\
f(11)= &1198651\\
f(12)= &9324047\\
f(13)= &78860687\\
f(14)= &719606005\\
f(15)= &7035514642\\
\end{array}$

http://oeis.org/A001428

====Subclasses====
[[Groups]] 

[[Commutative inverse semigroups]] 

====Superclasses====
[[Semigroups]] 


====References====

[(Ln19xx>
)]