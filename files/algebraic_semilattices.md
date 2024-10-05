=====Algebraic semilattices=====

Abbreviation: **ASlat**

====Definition====
An \emph{algebraic semilattice} is a [[complete semilattice]] $\mathbf{P}=\langle P,\leq \rangle $
such that

the set of compact elements below any element is directed and

every element is the join of all compact elements below it.

An element $c\in P$ is \emph{compact} if for every subset $S\subseteq P$ such that $c\le\bigvee S$, there exists
a finite subset $S_0$ of $S$ such that $c\le\bigvee S_0$.

The set of compact elements of $P$ is denoted by $K(P)$.

==Morphisms==
Let $\mathbf{P}$ and $\mathbf{Q}$ be algebraic semilattices. A morphism from $\mathbf{P}$ to 
$\mathbf{Q}$ is a function $f:P\rightarrow Q$ that is \emph{Scott-continuous}, which means that $f$ preserves all directed joins: 

$z=\bigvee D\Longrightarrow f(z)= \bigvee f[D]$


====Examples====
Example 1: 

====Basic results====


====Properties====
^[[Classtype]]  |second-order |
^[[Amalgamation property]]  | |
^[[Strong amalgamation property]]  | |
^[[Epimorphisms are surjective]]  | |
====Finite members====

$\begin{array}{lr}
f(1)= &1\\
\end{array}$


====Subclasses====
[[Algebraic lattices]] 


====Superclasses====
[[Algebraic posets]] 


====References====

[(Ln19xx>
)]