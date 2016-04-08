# dismathportfolio-saambautista
dismathportfolio-saambautista created by Classroom for GitHub

#BAUTISTA, Samantha Monique F. - EK

#Superman Assignment:
<UL>
<LI> a: superman is able to prevent evil
<LI> w: superman is willing to prevent evil
<LI> p: superman prevents evil
<LI> i: superman is impotent
<LI> m: superman is malevolent
<LI> e: superman exists
<LI> Premises and Conclusion
<LI> Premise 1: (a ^ w) → p
<LI> Premise 2: ¬a → i
<LI> Premise 3: ¬w → m
<LI> Premise 4: ¬p
<LI> Premise 5: e → (¬i ^ ¬m)
<LI> Conclusion: P1 ^ P2 ^ P3 ^ P4 ^ P5 → ¬e
<LI> By contraposition of Premise 5, not e is valid which concludes that superman does not exist:
<LI> P5: e → (¬i ^¬m) by contraposition
<LI> ¬(¬i ^ ¬m) → ¬e - De morgan's
<LI> (i & m) → ¬e
<LI> Solution:
<LI> a. Premise 1 by contraposition: ¬p → ¬(a ^ w)
<LI> b. By Modus Ponens Premise 4 and 1: ¬(a ^ w) - De Morgan's
<LI> c. ¬a & ¬w
<LI> d. Premise 2 transformed using A → B = ¬A & B: ¬¬a & i
<LI> e. Premise 3 transformed using A → B = ¬A & B: ¬¬w & m
<LI> f. Premise 2  & 3 combined using addition & associative with commutative properties: f1. ¬¬a & (i & m) f2. ¬¬w & (i & m)
<LI> g. f1. and f2. are transformed using A -> B = ¬A & B: 1. ¬a → (i & m) 2. ¬w -> (i & m)
<LI> h. By Disjunctive Elimination on c. f1. and f2.: (i & m)
<LI> i. By contraposition on Premise 5: (i & m) -> ¬e
<LI> j. By Modus Ponens on h. and i.: ¬e 
<LI> THEREFORE, SUPERMAN DOES NOT EXIST.
</UL>

#Week 1-3 
<UL>
<LI> Absent due to hospitalization
</UL>

#Week 4
<UL>
<LI> Vacuous and Trivial Proof were explained.
<LI> Method of Proof by Contradiction was discussed together with different examples.
<LI> Induction and Recursion were introduced to the class and an example was given.
<LI> There will always be a basis step before proceeding to the main process such as the inductive or recursive step.
<LI> The basis step is the assumption process while the inductive or recursive step is the step were the statement is proved.
</UL>

# DISMATH Project MIT Inventor App
# Screenshots
![alt tag](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-saambautista/blob/master/App.PNG)
![alt tag](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-saambautista/blob/master/App1.PNG)

#Week 5
<UL>
<LI> Recursive algorithm was discussed
<LI> Program Correctness 
      <UL>
      <LI> Program Verification - put input and see if it gives the correct output.
      <LI> Partial Correctness
            <UL>
            <LI> Initial Assertion, p, gives the properties that the input values must have.
            <LI> Final Assertion, q, the output.
            </UL>
      <LI> Hoare Triple: p{S}q where S is the program segment.
            <UL>
            <LI> Assume p ≡ T
            <LI> Substitute p to S, then show q ≡ T
            </UL>
      <LI> Proving of Compound Program - Rules of Inference
            p{S1}q
            q{S2}r
            ∴ p{S1:S2}r
      <LI>Proving Conditional Statements
            (p∧condition){S}q
            (p∧¬condition)→q
            ∴p{if condition then S} → q
      </UL>
<LI> Power Series
      <UL>
      <LI> Zeno's Paradox
      <LI> Represented by:
          ∞
          ∑ Anx^n = 1 + x + x^2 + x^3 +... 
          n=0
      </UL>
<LI> Set Theory 
      <UL>
      <LI> set is an unordered collection of distinct objects
      <LI> Empty Set/Null Set - { } = ∅ 
      <LI> Set-builder notation - { x| some property of x satisfies }
      </UL>
<LI> Venn Diagrams
      <UL> 
      <LI> A ∪ B - Union
      <LI> A ∩ B - Intersection
      <LI> A - B or A \ B - Difference
      </UL>
<LI> Set Identitites - same as logical equivalences F to ∅, T to U, p to A, q to B, ∧to ∩ and ∨ to ∪
<LI> Subsets - S ⊆ T (S is a subset of T)
<LI> Power Sets - ℘(S) = {T| T ⊆ S }; set of a subset
<LI> Superset - A ⊇ B
<LI> Cardinality - number of elements in a set
</UL>

#Week 6
<UL>
<LI> Review for Q1
<LI> Nested Quantifiers 
      <UL>
      <LI> The choices of x, some y, P(x,y) is true - ∀x∃yP(x,y)
      <LI> Some x, choices of y, P(x,y) is true- ∃x∀yP(x,y)
      <LI> Negation of Statements
      </UL>
<LI> Proof by cases
<LI> Proof by exhaustion
<LI> Existence Proofs
<LI> Uniqueness Proof
<LI> Functions
      <UL>
      <LI> function - assignment of exactly one element of B to each element of A; also called mappings or transformations 
      <LI> One-to-one Function (Injective)
      <LI> Onto Function (Surjective) - functions have equal range and codomain
      <LI> Bijective Function (Bijection) - both one-to-one and onto function
      <LI> Relation - not a function; one to many
      </UL>
</UL>

#Week 7
<UL>
<LI> Project 0.0 HelloWorld App 
</UL>

#Week 8
<UL>
<LI> Algorithm - a finite set of precise instructions for performing a computation or for solving a problem
<LI> Pseodocode - high level description of an algorithm that uses the structural conventions of a programming language, but intended for human reading; a human readable code
<LI> Searching Algorithms were discussed such as Linear Search and Binary Search
<LI> Linear Search - initial input is compared with the first element else proceeds to the next element and repeated until the element is located
<LI> Binary Search - initial input is compared to the middle term, if the input is larger, upper half is chosen else lower half. Process is repeated until element is located
</UL>

#Week 9
<UL>
<LI> Other Algorithms were discussed
<LI> Sorting Algorithms were discussed such as Bubble Sort, Insertion Sort and Greedy Algorithm
<LI> Bubble Sort - successively compares the adjacent elements and elements are interchanged if they are in the wrong order.Process is repeated until completely sorted
<LI> Insertion Sort - second element is compared to the first element, if second element is smaller than the first, it is placed before the first element else after. Process is repeated until completely sorted
<LI> Greedy Algorithm - selects the best choice at each step, instead of considering all sequences of steps that may lead to an optional solution; applied in optimization problems where a solution to the given problem either minimizes or maximizes the value of some parameter
</UL>

#Week 10
<UL>
<LI> Growth of Functions was discussed
<LI> Big-O, Big-Ω and Big-ϴ
<LI> Big-O Notation - looks for the upper bound of f(x)
      <UL>
      <LI> Common Big-O Estimates - n!, 2^n, n^2, n log n, n, log n, 1
      </UL>
<LI> Big-Ω - looks for the lower bound of f(x)
<LI> Big-ϴ - looks for both the upper and lower bound of f(x)
<LI> Time Complexity - can be expressed in terms of the number of operations used by the algorithms; number of comparisons will be used as the measure of the time complexity
      <UL>
      <LI> ϴ(1) - Constant complexity
      <LI> ϴ(log n) - Logarithmic Complexity
      <LI> ϴ(n) - Linear complexity
      <LI> ϴ(n log n) - n log n complexity
      <LI> ϴ(n^b) - Polynomial complexity
      <LI> ϴ(b^n), where b>1 - Exponential Complexity
      <LI> ϴ(n!) - Factorial Complexity
      </UL>
<LI> Division and Modulo
      <UL>
      <LI> let a = dq + r where a is an integer and d is a positive integer
      <LI> q = a div d - quotient
      <LI> r = a mod d - remainder(modulo)
      </UL>
</UL>

#Week 11
<UL>
<LI> HOLY WEEK
</UL>

#Week 12
<UL>
<LI> Final Project Requirements were discussed
<LI> Graph Theory
      <UL>
      <LI> Graph - discrete structures consisting of vertices and edges that connect the vertices.
      <LI> G = (V,E) where V is vertices and E is edges
      <LI> degree of a vertex in an undirected graph is the number of edges incident with it, except that the loop at a vertex contributes twice to the degree of that vertex
      </UL>
<LI> Handshaking Theorem
      <UL>
      <LI> Let G=(V,E) be an undirected graph with edges
        2e = ∑ deg(v)
            v=V
      </UL>
<LI> Subgraph of a graph
      <UL>
      <LI> G=(V,E) is a graph of H=(W,F), where W ⊆ V and F ⊆ E
      <LI> subgraph of H of G is a proper subgraph of G if H ≠ G
      </UL>
<LI> Path - sequence of edges that begins at a vertex of a graph and travels from vertex to vertex along edges of the graph
<LI> Euler Ciruit - a simple circuit that contains every edge of the graph; all nodes have even degrees; start and end of the circuit is the same
<LI> Euler Path - a simple path tha contains every edge of the graph; only one way path; exactly 2 nodes with odd degree
<LI> Euler's Formula - r = e - v + 2
<LI> Hamilton Circuit - a simple circuit passes through every vertex exactly once
<LI> Hamilton Path - a simple path passes through every vertex exactly once
<LI> Matrices of Graphs - adjacency matrix
<LI> Isomorphism of Graphs - isomorphic if there is a one-to-one and onto function from V1 to V2 with the property that a and b are adjacent in G1 if and only if f(a) and f(b) are adjacent in G2, for all a and b in V1
<LI>Planar Graph - drawn in the plane without edges having to cross
<LI> Nonplanar Graph - everything is interconnected to one another
</UL>

#Week13
<UL>
<LI> Homeomorphic Graphs - can be obtained from the same graph by a sequence of elementary subdivision
<LI> Elementary Subdivision - removing an edge and reconnecting it with a node at the middle; same graph, unequal number of nodes and edges
<LI> Graph Coloring- assignment of a color to each vertex provided that adjacent vertices does not have the same color; minimal use of color
      <UL>
      <LI> Chromatic number - least colors needed for a coloring of graph
      <LI> Four Color Theorem - only applies to planar graphs; chromatic number that is no greater than 4
      </UL>
<LI> Trees - connected undirected graph with no simple circuits; data structure with a set of linked nodes
<LI> Rooted Tree - a tree in which one vertex has been designated
      <UL>
      <LI> internal nodes - parents
      <LI> leaves - children
      </UL>
<LI> m-ary tree - every internal vertex has no more than m children
<LI> Ordered rooted tree - rooted tree where the children of each internal vertex are ordered
<LI> Tree traversal - Universal Address Systems
<LI> Preordered Traversal - ordered rooted tree; visit root (subtrees from left to right)
<LI> Inordered Traversal - visit leftmost subtree to the root to other subtrees from left to right
<LI >Postordered Traversal - visit subtrees left to right then to root
<LI> Modeling Computation
      <UL>
      <LI> Grammars - generate the words of a language and determine whether a word is in a language
      <LI> Language - generated by grammars; provides model for both natural language
      <LI> Finite-state machines
      <LI> Turing Machines
      </UL>
</UL>
