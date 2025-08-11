id: ccc

name: "Cartesian closed category"

definition: "A category with finite products and exponentials..."

associated_logics:
  * simply_typed_lambda_calculus
  * propositional_intuitionistic_logic (conjunction,implication fragment)
    
curry_howard:
 * implication: "exponentials (A ⇒ B or B^A)"
 * conjunction: "product"
 * truth: "terminal object"
   
examples:
  - Set (category of sets)
  - FinSet
   
references:
  - "Curry–Howard–Lambek"  # point to canonical refs
    
formalizations:
  - Coq: "https://github.com/..."

    
tags: ["lambda-calculus", "intuitionistic", "CCC"]
license: "Apache-2.0"
