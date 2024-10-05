=====First-order Theory=====

A \emph{first-order formula} is an expression constructed from atomic formulas combined with logical connectives 
$\mbox{not}, \mbox{and}, \mbox{or}, \Longrightarrow, \iff$ and quantifiers $\forall$, $\exists$ followed by
variables. 

The \emph{first-order theory} of a class of structures is the set of first-order formulas that hold in all members of the class.

The \emph{decision problem} for the first-order theory of a class of structures is the problem with input: a first-order formula
of length $n$ (as a string) and output: "true" if the formula holds in all members of the class, and "false" otherwise.

A first-order theory is \emph{decidable} if there is an algorithm that solves the decision problem, otherwise it is \emph{undecidable}.

A first-order theory is \emph{hereditarily undecidable} if every consistent subtheory is undecidable.

The complexity of the decision problem (if known) is one of PTIME, NPTIME, PSPACE, EXPTIME, ...

The completeness theorem for first-order logic, due to Kurt Gödel, provides a complete deductive system for first-order logic,
and shows that a set of formulas is a first-order theory of a class of structures (of the appropriate language) if and only if it is
closed under the 'usual' rules of logical deduction.
