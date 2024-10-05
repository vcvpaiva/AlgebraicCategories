=====Directed complete partial orders=====

Abbreviation: **DCPO**
====Definition====
A \emph{directed complete partial order} is a poset $\mathbf{P}=\langle P,\leq \rangle $
such that every directed subset of $P$ has a least upper bound: 
$\forall D\subseteq P\ (D\ne\emptyset\mbox{and}\forall x,y\in D\ \exists z\in D
(x,y\le z)\Longrightarrow \exists z\in P(z=\bigvee D))$.
==Morphisms==
Let $\mathbf{P}$ and $\mathbf{Q}$ be directed complete partial orders. A morphism from $\mathbf{P}$ to 
$\mathbf{Q}$ is a function $f:Parrow Q$ that is \emph{Scott-continuous}, which means that $f$ preserves all directed joins: 

$z=\bigvee D\Longrightarrow f(z)= \bigvee f[D]$

====Examples====
Example 1: $\langle \mathbb{R},\leq \rangle $, the real numbers with the standard order.
Example 1: $\langle P(S),\subseteq \rangle $, the collection of subsets of a
sets $S$, ordered by inclusion.


====Basic results====

====Properties====
^[[Classtype]]  |second-order |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |
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
[[Complete semilattices]] 

====Superclasses====
[[Directed partial orders]] 


====References====

[(Ln19xx>
)]