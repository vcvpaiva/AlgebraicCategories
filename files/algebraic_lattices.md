# Algebraic Lattices

Abbreviation: **ALat**

## Definition
An ***algebraic lattice*** is a [complete lattice](complete_lattices.md) $\mathbf{A}=\langle A,\bigvee,\bigwedge\rangle$ such that
every element is a join of compact elements.

An element $c\in A$ is ***compact*** if for every subset $S\subseteq A$ such that $c\le\bigvee S$, there exists
a finite subset $S_0$ of $S$ such that $c\le\bigvee S_0$.

### Morphisms
Let $\mathbf{A}$ and $\mathbf{B}$ be algebraic lattices. 
A morphism from $\mathbf{A}$ to $\mathbf{B}$ is a function $h:A\rightarrow B$ that is a complete homomorphism: 

$h(\bigvee S)=\bigvee h[S] \text{ and } h(\bigwedge S)=\bigwedge h[S]$

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


## Subclasses
[Algebraic distributive lattices](algebraic_distributive_lattices.md) 


## Superclasses
[Complete lattices](complete_lattices.md) 

[Algebraic semilattices](algebraic_semilattices.md) 


## References






