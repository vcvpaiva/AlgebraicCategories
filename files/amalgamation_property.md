# Amalgamation Property

An ***amalgam*** is a tuple 
$\langle \mathbf{A},f,\mathbf{B},g,\mathbf{C}\rangle$ such that 
$\mathbf{A},\mathbf{B},\mathbf{C}$ are structures of the same 
signature, and $f:\mathbf{A}\to\mathbf{B}$, $g:\mathbf{A}\to\mathbf{C}$
are embeddings (injective morphisms).

A class $\mathcal{K}$ of structures is said to have the
***amalgamation property*** if for every amalgam $\langle \mathbf{A},f,\mathbf{B},g,\mathbf{C}\rangle$ with 
$\mathbf{A},\mathbf{B},\mathbf{C}\in\mathcal{K}$ and $A\neq\emptyset$
there exists a structure $\mathbf{D}\in\mathcal{K}$ and embeddings 
$f':\mathbf{B}\to\mathbf{D}$, $g':\mathbf{C}\to\mathbf{D}$ such that
$f'\circ f=g'\circ g$.
