=====Regular semigroups=====

Abbreviation: **RSgrp**
====Definition====
An element $x$ of a semigroup $S$ is said to be \emph{regular} if exists $y$ in $S$ such that $xyx=x$. 

====Definition====
A \emph{regular semigroup} is a [[semigroups]] $\mathbf{S}=\langle
S,\cdot \rangle $ such that
each element is regular.


====Definition====
A \emph{regular semigroup} is a structure $\mathbf{S}=\langle
S,\cdot \rangle $, where $\cdot $ is an infix binary operation, called
the \emph{semigroup product}, such that


$\cdot $ is associative:  $(xy)z=x(yz)$


each element is \emph{regular}:  $\exists y(xyx=x)$

====Definition====
We say that $y$ is an \emph{inverse} of an element $x$ in a semigroup $S$ if $x=xyx$ and $y=yxy$.  


==Morphisms==
Let $\mathbf{S}$ and $\mathbf{T}$ be regular semigroups. A morphism from 
$\mathbf{S}$ to $\mathbf{T}$ is a function $h:Sarrow T$ that is a
homomorphism: 

$h(xy)=h(x)h(y)$

====Examples====
Example 1: $\langle T_X,\circ\rangle $, the \emph{full transformation semigroup} of functions on $X$, with composition.

$\langle End(V),\circ\rangle $, the \emph{endomorphism monoid} of a vector space $V$, with composition.



====Basic results====
If $x$ is a regular element of a semigroup (say $x=xyx$), then $x$ has an inverse, namely $yxy$, since $x=x(yxy)x$ and $yxy=(yxy)x(yxy)$. 

====Properties====
^[[Classtype]]  |First-order |
^[[Equational theory]]  | |
^[[Quasiequational theory]]  | |
^[[First-order theory]]  | |
^[[Locally finite]]  |No |
^[[Residual size]]  | |
^[[Congruence distributive]]  |No |
^[[Congruence modular]]  | |
^[[Congruence n-permutable]]  | |
^[[Congruence regular]]  | |
^[[Congruence uniform]]  | |
^[[Congruence extension property]]  | |
^[[Definable principal congruences]]  | |
^[[Equationally def. pr. cong.]]  |No |
^[[Amalgamation property]]  |No |
^[[Strong amalgamation property]]  |No |
^[[Epimorphisms are surjective]]  | |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
f(2)= &3\\
f(3)= &9\\
f(4)= &42\\
f(5)= &206\\
f(6)= &1352\\
f(7)= &10168\\
f(8)= &91073\\
f(9)= &925044
\end{array}$

(the opposite of a semigroup $S$ is identified with $S$ in the table above, see https://oeis.org/A001427)

====Subclasses====
[[Bands]] 

[[Inverse semigroups]] 

[[Completely regular semigroups]] 

====Superclasses====
[[Semigroups]] 


\begin{bibdiv}
\begin{biblist}

\bib{MR1455373}{book}{
   author={Howie, John M.},
   title={Fundamentals of semigroup theory},
   series={London Mathematical Society Monographs. New Series},
   volume={12},
   note={Oxford Science Publications},
   publisher={The Clarendon Press Oxford University Press},
   place={New York},
   date={1995},
   pages={x+351},
   isbn={0-19-851194-9},
   review={\MR{1455373 (98e:20059)}},
}

\end{biblist}
\end{bibdiv}

