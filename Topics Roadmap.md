Based on the sources provided, here is a roadmap of topics organized into the five blocks you requested:

### **Block 1: Regular Languages and Finite Automata**
*   **Formal Language Basics:** Definitions of alphabets, words, and languages; operations on words (concatenation, reverse, length) and operations on sets/languages (union, intersection, complement, Kleene star).
*   **Regular Expressions (RE):** Syntax and semantics of regular expressions; using REs to define languages and for practical applications like pattern matching and lexical analysis.
*   **Deterministic Finite Automata (DFA):** Formal definition (5-tuple); state diagrams and transition tables; language acceptance and the extended transition function ($\delta^*$).
*   **Non-deterministic Finite Automata (NFA):** Concept of non-determinism and $\Lambda$-transitions; equivalence between NFAs and DFAs via the subset construction.
*   **Transformations:** Systematic methods to convert between REs and NFAs, and between NFAs and DFAs.

### **Block 2: Propositional and Predicate Logic**
*   **Propositional Logic:** Syntax (variables and connectives like $\wedge, \vee, \neg, \to$); semantics using truth tables; notions of validity (tautologies), satisfiability, and entailment.
*   **Proof Systems for Propositional Logic:** Natural deduction rules (introduction and elimination); Fitch-style "Box Proofs"; soundness ($ \Gamma \vdash \phi \Rightarrow \Gamma \vDash \phi $) and completeness ($ \Gamma \vDash \phi \Rightarrow \Gamma \vdash \phi $).
*   **Sets, Relations, and Functions:** Formal definitions of relations (equivalence relations, quotient sets) and functions (one-to-one, onto, bijective) as foundational tools for logic.
*   **Predicate Logic (First-Order Logic):** Syntax including quantifiers ($\forall, \exists$), constants, functions, and predicates; semantics involving models and universes of discourse; proof rules for quantifiers.
*   **Properties and Applications:** Expressiveness of predicate logic (reachability limitations); decidability status; applications in databases (SQL) and programming (Prolog).

### **Block 3: Regular and Context-Free Languages**
*   **DFA Minimization and Myhill-Nerode:** Distinguishability of strings; Myhill-Nerode theorem; algorithm for finding the unique minimal DFA for a regular language.
*   **Limits of Regular Languages:** The Pumping Lemma for regular languages used to prove non-regularity (e.g., $\{a^n b^n \mid n \geq 0\}$); closure properties (intersection, complement).
*   **Context-Free Grammars (CFG):** Formal definition; derivations and derivation trees; regular grammars as a subset; ambiguity in grammars.
*   **Chomsky Normal Form (CNF) and Parsing:** Transforming CFGs into CNF by eliminating null and chain rules; the CYK algorithm for checking word membership.
*   **Push-down Automata (PDA):** Extending finite automata with an unbounded stack; acceptance by final state or empty stack; equivalence between CFGs and PDAs; Deterministic PDAs (DPDA) and their limits.
*   **Context-Free Language Properties:** The Pumping Lemma for CFLs; closure properties (closed under union, concatenation, star; NOT closed under intersection or complement); decidability of membership and emptiness vs. undecidability of universality and ambiguity.

### **Block 4: Turing Machines and Decidability**
*   **Turing Machines (TM) Basics:** A general model of computation; infinite tape memory; formal definition (states, tape alphabet, transition function); TMs as language acceptors and function computers.
*   **TM Variations:** Multi-tape TMs; non-deterministic TMs (NTM); the Church-Turing thesis (TMs represent the limit of algorithmic procedures); the Universal Turing Machine (UTM) as an interpreter.
*   **Recursive and Recursively Enumerable (RE) Languages:** Difference between accepting (RE) and deciding (recursive) a language; enumeration of languages in canonical order.
*   **Undecidability:** Proof by contradiction and diagonalization; the Halting Problem and its undecidability; Cantor’s theorem on uncountable sets (uncountably many non-recursive languages).
*   **Grammars and the Chomsky Hierarchy:** Unrestricted grammars and their equivalence to TMs; the hierarchy of language types (Regular $\subset$ Context-Free $\subset$ Context-Sensitive $\subset$ RE).
*   **Problem Reductions:** Reducing one decision problem to another ($P \leq Q$); Rice’s Theorem (all non-trivial language properties of TMs are undecidable); Post’s Correspondence Problem (PCP).

### **Block 5: Logic, Arithmetic, Incompleteness & Complexity**
*   **Peano Arithmetic (PA):** Axiomatization of natural numbers; expressing mathematical concepts (primes, Goldbach conjecture) using arithmetic macros; induction schemes.
*   **Gödel’s Incompleteness Theorems:** The limits of axiomatization; arithmetic can express its own consistency and undecidable problems like APCP; Gödel numbering; existence of true but unprovable statements in PA.
*   **Computational Complexity:** Turning from computability to efficiency; Big-Oh notation; time complexity for deterministic vs. non-deterministic TMs.
*   **Classes P and NP:** Definition of Class P (feasible computations) and Class NP (feasible verifiability); the P vs. NP question.
*   **NP-Completeness:** Polynomial-time reductions ($L_1 \leq_P L_2$); NP-hardness; the Cook-Levin Theorem (SAT is NP-complete); practical examples like Clique, 3-SAT, and scheduling.
*   **Applications of Complexity:** Practical use of SAT solvers for program verification, planning, and optimization.
