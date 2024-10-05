=====Notation and Terminology=====

=== This page describes the conventions that are used for the entries in the database ===

\emph{Sets } are denoted by upper-case roman letters, usually $A, B, C,\ldots, U, V, W$. 

$\mathbb{N}=$ the set of natural numbers $=\{0,1,2,\ldots\}$,\\
$\mathbb{Z}=$ the set of integers $=\mathbb{N}\cup\{-n:n\in\mathbb{N}\}$,\\
$\mathbb{Q}=$ the set of rationals $=\{m/n:m,n\in\mathbb{Z}, n>0\}$,\\
$\mathbb{R}=$ the set of real numbers,\\
$\mathbb{C}=$ the set of complex numbers $=\{x+iy:x,y\in\mathbb{R}\}$.\\

$\mathcal P(A)=\{S:S\subseteq A\}$, the power set of $A$.\\
$A^n=\{\langle a_0,\ldots,a_{n-1}\rangle:a_0,\ldots,a_{n-1}\in A\}$, the set of all $n$-tuples of elements of $A$.

\emph{Elements of sets} are denoted by lower-case roman letters, usually $a, b, c, d, e$.\\
\emph{Variables that range over elements} are denoted by lower-case roman letters, usually $x, y, z, u, v, w, x_0, x_1, \ldots$.\\
\emph{Integer variables} are usually denoted by $i,j,k,m,n$.\\
\emph{Variables that range over sets} are denoted by upper-case roman letters, usually $X, Y, Z, X_0, X_1, \ldots$

\emph{Functions} are denoted by lower-case roman letters, usually $f, g, h$.

A \emph{(first-order) operation} on a set $A$ is a function from $A^n$ to $A$, where $n\ge 0$ is the arity of the operation. If $n=0$ then the
operation is called a \emph{constant}.

A \emph{(first-order) relation} on a set $A$ is a subset of $A^n$, where $n>0$ is the arity of the relation.

A \emph{second-order operation} on a set $A$ is a function from $\mathcal P(A)^n$ to $A$.

A \emph{second-order relation} on a set $A$ is a subset of $\mathcal P(A)^n$.

A \emph{mathematical structure} is a tuple of the form $\mathbf{A}=\langle A,\ldots\rangle$ where $A$ is a set and
$\ldots$ specifies a list of (possibly higher-order) operations and relations on $A$. 
