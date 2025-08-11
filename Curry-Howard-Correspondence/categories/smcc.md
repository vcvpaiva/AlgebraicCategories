id: smcc

name: "symmetric monoidal closed category"

definition: "A category with finite tensor products and internal-hom..."

associated_logics:
  - simply_linear_typed_lambda_calculus
  - propositional_multiplicative_linear_logic
   
curry_howard:
  implication: "internal hom (A -o B or [A,B])"
  conjunction: "tensor product" ($\otimes$)
  truth: "unit object" $I$

examples:
  - Set (category of sets)
  - FinSet
    
references:
  - "Curry–Howard–Lambek"  # add ref
    
formalizations:
  - Coq: "https://github.com/..."

    
tags: ["lambda-calculus", "intuitionistic", "CCC"]
license: "Apache-2.0"
