# Partially ordered sets

Abbreviation: **Pos**
## Definition
A ***partially ordered set*** (also called ***ordered set*** or ***poset*** for short) is a structure $\mathbf{P}=\langle P,\leq \rangle$
such that $P$ is a set and $\leq$ is a binary relation on $P$ that is


reflexive:  $x\leq x$


transitive:  $x\leq y$, $y\leq z\Longrightarrow x\leq y$


antisymmetric:  $x\leq y$, $y\leq x\Longrightarrow x=y$.
## Definition
A ***strict partial order*** is a structure $\langle P,<\rangle$
such that $P$ is a set and $<$ is a binary relation on $P$ that is


irreflexive:  $\neg(x<x)$


transitive:  $x<y$, $y<z\Longrightarrow x<y$


Remark: 
The above definitions are related via: $x\leq y\Longleftrightarrow x<y \text{or} x=y$ and 
$x<y\Longleftrightarrow x\leq y$, $x\neq y$.

For a partially ordered set $\mathbf{P}$, define the dual $\mathbf{P}^{\partial }=\langle P,\geq \rangle$ by $x\geq
y\Longleftrightarrow y\leq x$. Then $\mathbf{P}^{\partial }$ is also a
partially ordered set.


### Morphisms
Let $\mathbf{P}$ and $\mathbf{Q}$ be posets. A morphism from $\mathbf{P}$ to 
$\mathbf{Q}$ is a function $f:P\to Q$ that is order-preserving: 

$x\leq y\Longrightarrow f(x)\leq f(y)$

## Examples
Example 1: $\langle \mathbb{R},\leq \rangle$, the real numbers with the standard order.

Example 2: $\langle P(S),\subseteq \rangle$, the collection of subsets of a
sets $S$, ordered by inclusion.

Example 3: Any poset is order-isomorphic to a poset of subsets of some set, ordered by
inclusion.



## Basic results

## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |Universal Horn class |
|[Universal theory](universal_theory.md)  |Decidable |
|[First-order theory](first-order_theory.md)  |Undecidable |
|[Amalgamation property](amalgamation_property.md)  | |
|[Strong amalgamation property](strong_amalgamation_property.md)  | |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  | |
## Finite members

$\begin{array}{lr}
f(1)= &1\\
f(2)= &2\\
f(3)= &5\\
f(4)= &16\\
f(5)= &63\\
f(6)= &318\\
f(7)= &2045\\
f(8)= &16999\\
f(9)= &183231\\
f(10)= &2567284\\
f(11)= &46749427\\
f(12)= &1104891746\\
f(13)= &33823827452\\
f(14)= &1338193159771\\
f(15)= &68275077901156\\
f(16)= &4483130665195087
\end{array}$

http://oeis.org/A000112

## Subclasses
[Connected partial orders](connected_partial_orders.md) 

[Complete partial orders](complete_partial_orders.md) 

[Directed partial orders](directed_partial_orders.md) 

## Superclasses
[Preordered sets](preordered_sets.md) 


## References


)]