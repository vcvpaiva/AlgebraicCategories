# Topological spaces

Abbreviation: **Top**

## Definition
A ***topological space*** is a structure $\mathbf{X}=\langle X,\tau\rangle$, 
where $\tau=\Omega(\mathbf{X})\subseteq \mathcal P(X)$
is a collection of subsets of $X$ called the ***open sets of*** $\mathbf{X}$ such that


any union of open sets is open:  $\mathcal{U}\subseteq\Omega(\mathbf{X})\Longrightarrow\bigcup\mathcal{U}\in\Omega(\mathbf{X})$


any finite intersection of open sets is open:  $U,V\in\Omega(\mathbf{X})\Longrightarrow U\cap V\in\Omega(\mathbf{X})$ and $X\in\Omega(\mathbf{X})$

Remark: Note that the union of an empty collection is empty, so $\emptyset\in\Omega(\mathbf{X})$.

The set of ***closed sets of*** $\mathbf{X}$ is $K(\mathbf{X})=\{X-U\mid U\in\Omega(\mathbf{X})\}$.


### Morphisms
Let $\mathbf{X}$ and $\mathbf{Y}$ be topological spaces. 
A morphism from $\mathbf{X}$ to $\mathbf{Y}$ is a function $f:X\rightarrow Y$ that is ***continuous***: 

$V\in\Omega(\mathbf{Y})\Longrightarrow f^{-1}[V]\in\Omega(\mathbf{X})$

## Examples
Example 1: 

## Basic results


## Properties


|Property|Value|
|---|---|
|[Classtype](classtype.md)  |second-order |
|[Amalgamation property](amalgamation_property.md)  |yes |
|[Strong amalgamation property](strong_amalgamation_property.md)  |yes |
|[Epimorphisms are surjective](epimorphisms_are_surjective.md)  |yes |

Remark: 
The properties given above use an $(\mathcal{E},\mathcal{M})$ factorization system with $\mathcal{E}=$ surjective morphisms and
$\mathcal{M}=$ embeddings.


## Subclasses
[T0-spaces](t0-spaces.md) 


## Superclasses
[Sets](sets.md) 


## References
