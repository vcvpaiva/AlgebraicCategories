=====Quasiequational theory=====

A \emph{quasiequation} is a universal formula of the form $\phi_1 \mbox{ and } \phi_2 \mbox{ and }\cdots\mbox{ and } \phi_m\ \Longrightarrow\ \phi_0$,
where the $\phi_i$ are atomic formulas. Note that for an algebraic language, the $\phi_i$ are simply equations. For $m=0$, a quasiequation
is just a universal atomic formula.

The \emph{quasiequational theory} of a class of structures is the set of quasiequations that hold in all members of the class.

The \emph{decision problem} for the quasiequational theory of a class of structures is the problem with input: a quasiequation
of length $n$ (as a string) and output: "true" if the quasiequation holds in all members of the class, and "false" otherwise.

The quasiequational theory is \emph{decidable} if there is an algorithm that solves the decision problem, otherwise it is \emph{undecidable}.

The complexity of the decision problem (if known) is one of PTIME, NPTIME, PSPACE, EXPTIME, ...

A complete deductive system for quasiequations is given in [A. Selman, \emph{Completeness of calculi for axiomatically defined classes of algebras}, 
Algebra Universalis, \textbf{2}, 1972, 20--32 [[http://www.ams.org/mathscinet-getitem?mr=47:1725|MRreview]].
Additional information on quasiequations can be found e.g. in
[[http://www.thoralf.uwaterloo.ca/htdocs/ualg.html|Stanley N. Burris and H.P. Sankappanavar, A Course in Universal Algebra]].

