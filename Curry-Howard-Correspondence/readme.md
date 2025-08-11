A compact, practical plan to drop into the repository. 

It’s tailored so the knowledge-base contains only categories that have a clear Curry–Howard (proofs-as-programs / formulae-as-types / internal language) relationship to logics. 

Includes:
* (1) scope and goals,
* (2) a recommended data model and file layout,
* (3) the canonical category ↔ logic mappings to include, with references,
* (4) an ingestion / curation pipeline, and
* (5) concrete first tasks one can assign as issues.


Add canonical references for the mappings so one can check sources. 

------------------------------------------

Project scope & goals

    Scope: add, standardize, and interlink entries for categories that serve as models of logics (via Curry–Howard or its extensions) — e.g. cartesian closed categories, locally cartesian closed categories, *-autonomous categories, toposes, categories-with-families, monoidal closed categories, etc. 
    Exclude categories that have no recognized correspondence to a logic/lambda calculus.

    Goals:

       * For each category, document the category-theoretic definition, associated logic(s), and the precise Curry–Howard mapping (what syntactic constructors correspond to which categorical structure).

       * Provide canonical examples, references (papers, arXiv, books), and links to formalizations (Coq/Agda/Lean) when available.

       * Make the dataset machine-readable (JSON-LD / YAML / RDF) so other projects (MathGloss, Mathoscope, MathNLI, etc.) can ingest it.

       * Provide clear “how to use” docs and issue/PR templates so the community can add further validated entries.

    Why this is useful: makes explicit the web of models for programming-language and logic phenomena; helpful for researchers building formalizations, semantics, or educational material.

--------------------------------------------

Repository layout and data model

New top-level folders (minimal, composable):

/files/               # existing content area (repo already uses files/)
  index.md
  categories/         # one file per category (markdown + frontmatter)
  logics/             # short pages describing the logics
  mappings/           # JSON-LD/YAML files: explicit Curry–Howard mappings
  examples/           # concrete examples and formalization links
  bibliographies/     # bibtex / recommended reading per entry
  templates/          # PR/Issue/entry templates

Example frontmatter schema (YAML) for categories/ccc.md

id: ccc
name: "Cartesian closed category"
definition: "A category with finite products and exponentials..."
associated_logics:
  - simply_typed_lambda_calculus
  - propositional_intuitionistic_logic
curry_howard:
  implication: "exponentials (A ⇒ B or B^A)"
  conjunction: "product"
  truth: "terminal object"
examples:
  - Set (category of sets)
  - FinSet
references:
  - "Curry–Howard–Lambek"  # point to canonical refs
formalizations:
  - Coq: "https://github.com/..."
tags: ["lambda-calculus", "intuitionistic", "CCC"]
license: "Apache-2.0"

Mapping files

    mappings/ccc-mapping.yaml — record the exact syntactic ↔ categorical correspondence and short equational laws used in the proof.

    Use JSON-LD context so later you can export RDF/OWL if desired for semantic-web linking.

-----------------------------------------------------    

Canonical categories & their logic correspondences (starter list)

Each item below should have an entry in categories/, a summary in logics/, and a mappings/ file describing the Curry–Howard translation.

    Cartesian Closed Categories (CCC)

        Models: simply-typed λ-calculus / intuitionistic propositional logic (implication = exponentials, conjunction = product, truth = terminal).

        Use as canonical citation: Curry–Howard–Lambek correspondence.
        Wikipedia

    Toposes

        Models: higher-order intuitionistic logic / internal language of a topos; subobject classifier Ω implements propositions.

        Useful for: predicate logic, higher-order reasoning, internal set-like semantics.
        NCAT Lab

    Locally Cartesian Closed Categories (LCCC)

        Models: dependent type theories with Π (dependent product) and Σ (dependent sum) types — the categorical semantics for dependent types and (some) Martin-Löf type theory variants.
        NCAT Lab
        math.mcgill.ca

    Categories with Families / Contextual Categories / Comprehension Categories

        Models: syntactic/dependent type theory; these are the categorical structures that express syntax (contexts, substitution) more explicitly than LCCC in some settings. (Add references to Cartmell, Dybjer, Awodey et al. in the entry.)

    *-Autonomous / Symmetric Monoidal Closed Categories

        Models: (fragments of) linear logic; dualizing objects capture linear negation and resource-sensitivity. Include Barr and Seely references.
        math.mcgill.ca
        Stanford Encyclopedia of Philosophy

    Heyting algebras / Locales

        Models: propositional intuitionistic logic (algebraic semantics). Good entry for simpler propositional correspondences (proofs ↔ order relations). (Include nLab / standard textbooks.)

    Cartesian closed bicategories, monoidal categories with modalities, and categorical models for modal logics

        Modalities ↔ monads/comonads or indexed adjoints. (Add references and examples; these are often higher/2-categorical.)

    (Optional/Advanced) ∞-Categorical models (∞-toposes)

        Models: Homotopy Type Theory (HoTT) and higher inductive types — link to ∞-toposes and ∞-groupoid semantics. Mark as advanced and require specialized references.

(For every item, include: definition, minimal axioms, explicit Curry–Howard mapping, canonical examples, formalizations, references.)

--------------------------------------------------------

