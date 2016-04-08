# dismathportfolio-Green-Dream-Giant
dismathportfolio-Green-Dream-Giant created by Classroom for GitHub


This portfolio is owned by Mikhael Willard R. Songco
- From section EK


**REMINDER**: PLEASE PUT EXAMPLES ON EVERY TOPIC DISCUSSED IN ORDER TO UNDERSTAND FURTHER THE PROBLEM!




##WEEK 1:

Here we go, it's time to learn my DISMATH (again). Introductions are still introductions; nothing new, except I'm getting ready for it this time. Luckily, it's my favorite teacher again, Mr. Melvin and that guy intrigues me, and he's quite jolly all the time. I met Vin and Mel again. This time, I knew all too well who's the Knight and the Knave without remembering back then. I guess things may not look so dark for me after all.

- Definition of Discrete Mathematics - Study of distinct & countable objects.

Ah yes, the propositions and the truth tables. How many times do you see **p** and **q** in other Math subjects? Either way, these guys will save me a couple of times later on.

- PROPOSITION - Declarative statement with a truth value (either true (T) or false (F), but not both.
- NOT PROPOSITION - Commands (Imperative), Questions (Interrogative), and statements that are neither true nor false

- Compound Proposition - Propositions combined by using logical operators/connectives.

Oh, and don't forget the connectives as well: ¬ for **not**, ∧ for **and**, ∨ for **or**,⊕ for  **xor**, → for **conditional (Only if)** and ↔ for **biconditional (If and only if)**.

- Here's all of the conditions in a table:

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

- Things to NOTE 1:
   - Negation - Opposite of its truth value (T to F, and F to T)
   - Conjunction - Find the minimum truth value (which would be F if there is)
   - Disjunction - Find the maximum truth value (which would be T if there is)
   - Exclusive - Either, maximum (T); Both, minimum (F)
   - Conditional - *q* should be maximum, otherwise (F)
   - Biconditional - *p* and *q* must be equal, otherwise (F)

- And here's the Truth Table applicable to **p** and **q**:

| p  |  q | ¬p | p ∧ q | p v q | p ⊕ q | p → q | p ↔ q | 
|:---:|:---:|:---:|:-----:|:-----:|:-----:|:-----:|:-----:|
| F | F | T | F | F | F | T | T |
| F | T | T | F | T | T | T | F |
| T | F | F | F | T | T | F | F |
| T | T | F | T | T | F | T | T |

- Contrapositive, Converse, and Inverse of the Conditional Statement:
   - Inverse of p → q:
     - **¬p → ¬q**
   - Converse of p → q: 
     - **q → p**
   - Contrapostive of p → q:
     - **¬q → ¬p**
     - (Note that: p → q ≡ ¬q → ¬p)

I need to learn all of these; they will save my life.

Also, I almost forgot. To check the number of tables needed in order to solve a specific number of propositions, I'll keep this formula in mind:
- No. of tables = 2^n, where n: No. of propositional values (p,q,r..) found in the sentence/s.

##WEEK 2:

We started a very long proposition. That means there's a lot sentences where every one of them there's at least to or three propositions identified and connectives as well. This means the Truth table was not optional in solving these types of problems. And there's many more types of similar problems that I have to watch out for as well.

- Logical Equivalence - Compound propositions that have the same truthvalues in all possible cases are called logically equivalent.
- Propositions p and q are logically equivalent.
   - (P ≡ Q) if P → Q is a tautology.

- Propositional Logic - Area of logic that deals with propositions. (One or two sentences)

- Predicate Logic
   - Concerned not only with logic relations between sentences or propositions as wholes, but also their internal structure in terms of subject and predicate. (Uses in three or more sentences; this will be explained later on)
   - Is the area of logic that deals withpredicates and quantifiers.

I need to understand and practice using logical equivalences because they are very tricky, and unless I understand them completely, I need to memorize the key concepts. I can simplify a logical statement using logical equivalences, as an alternative to the Truth table approach, but the problem is, **the shortcut is not always the shortcut**, mind you.

- Different Types of Logical Equivalences:
    - Identity laws
    - Domination laws
    - Idempotent laws
    - Double negation law
    - Commutative laws
    - Associative laws
    - Distributive laws
    - De Morgan's laws
    - Absorption laws
    - Negation laws


By the way, I did the Superman homework thing in class in fifteen minutes! Although I have miss some codes, I think I got it right, and I kind of made sure of that. (Note: Superman does not exist!)

The quantifiers are next in my list that I really need to focus on right now, and these guys are quite hard and confusing, and if I don't understand their principles, I'm going to have a bad time! Hehehe...

- Quantifiers - It indicates the generality of the open sentence in which a variable occurs.
    - Existential quantifier (∃x)Px - "there Exist"
    - Universal quantifier (∀x)Px - "for All"

I find the implication most confusing, especially when the expression is no longer "if p, then q".

The rules of inference might be easy, but atm it is quite confusing, and they are the ones that I need to memorize in order to use this tool properly. This tool should be the one that I used on the Superman problem rather than the logical equivalence which took quite long.

- Rules of Inference - Another set of tools use to proof if the statement is valid (Tautology) or not (Fallacy) by examining its premises.
 
| Rules of Inference | Tautology | Name |
| :---------: | :--------------: | :----------: |
| p, p → q ∴ q | (p ∧ (p → q)) → q | Modus ponens |
| ¬q, p → q ∴ ¬p | (¬q ∧ (p → q))→¬p | Modus tollens |
| p → q, q → r ∴ p → r | ((p → q) ∧ (q → r)) → (p → r) | Hypothetical syllogism |
| p ∨ q, ¬p ∴ q | ((p ∨ q)∧¬p) → q | Disjunctive syllogism |
| p ∴ p ∨ q | p → (p ∨ q) | Addition |
| p ∧ q ∴ p | (p ∧ q) → p | Simplification |
| p, q ∴ p ∧ q | ((p) ∧ (q)) → (p ∧ q) | Conjuction |
| p ∨ q, ¬p ∨ r ∴ q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) | Resolution |

My professor said that if I've read the book just this week, I'm in danger. but I don't think I am that much in danger, because I have read and practice some problems, but still, I have to be extremely cautious.

##WEEK 3:

Our professor teaches us the method of proving, the core prime of the subject, and one of the most confusing and difficult to understand and use. This is because it requires heavy algebra and there's no formal or direct indicator of what previous tools to use.

Here are the different **Methods of PROOF**:
- Direct Proof
    - 1. Assume *p* is **TRUE**
    - 2. **Show** that *q* is also True (using no. 1)
- Proof By Contrapostion
    - 1. Assume *¬q* is **TRUE**
    - 2. **Show** that *¬p* is also True
- Vacuous and Trivial Proof
    - 1. Show that *p* is *False* or *q* is *True* 
    - 2. p → q must be *True*
    - Vacuous (FF, FT, TT) Trivial
       - Note: Only use Vacuous or Trivial if and only if one of them is certain.
- Proof by Contradiction
    - Show that *assuming ¬p is true* leads to a **Contradiction**.
       - Note: Always know the meaning and priciples of the statement before prroving it with a contradiction.

You have to be careful with them, so far, they are the **most difficult** to understand and use. I need to learn and practice with them vigorously in order for me to use them properly.

##WEEK 4:

Okay, this week he added a new method of proof and another two topics that includes proving and other previous subjects.

- Proof by Equivalence - To prove the biconditional statement premise, both P → Q and Q → P must be **TRUE** by using other proving methods.
    - (p ↔ q) ↔ [(p → q) ∧ (q → p)]

- **Mathematical Induction** - *Substitution (Basis Step)* + *Direct Proof (Inductive Step)*
    - 1. Basis Step: P(0) or P(1) is shown to be True
    - 2. Inductive Step: Use Direct Proof in order to justify P(0) or P(1)
    - **Examples**

- **Recursive/Inductive Definition** - *Substitution (Basis Step)* + *Recursive Step*
    - 1. Basis Step: P(0) or P(1) is shown to be True
    - 2. Recursive Step: Give a rule for finding its value at an integer from its original statement
    - **Examples**

##WEEK 5:

We continued discussing Recursions, or at least Recursive Definition, and gave us a lot of example as the funtion reffered to its original statement in order to find the value that was looking for. In this week, we were tackling now about algorithms (w/ a little programming), from Recursion Algorithm to Partial Correctness (Feb 9).

Definition of an **Algorithm**
 - A finite set of precise instructions for perfoming a computation/solving a problem.
 
 - Recursive Algorithm - An algorithm is called recursive if it solves a problem by reducing it to an instance of the same problem with a smaller input.
    - **Examples**
       - What is the recursive definition for *computing* n! ?
       - Give a recursive algorithm for computing a^n, where: a = nonzero Real number ; n = nonnegative Integer.

 **Program Correctedness** (for programming)
  - We need a proof to show that the program always gives the correct output (by Program Verification)
     - P(x) = "correct output"
     - x = input
     - (∀x)P(x) ≡ T

*Program Verification*
 - 1. Show that the correct answer is obtained if the program terminates. (**Partial Correctedness/Substitution**)
 - 2. Show that the program is true by proving. (Higher/Advanced Course)

 - **Partial Correctness**
    - 1. Initial assertion p,
    - 2. Final assertion q,

 - *Hoare Triple*: p{S}q, where;
    - **p** is the initial assertion
    - **{S}** is the program segment
    - **q** is the final assertion
    - Similar to *Direct Proof*
       - 1. Assume p is True
       - 2. Substitute p to the program S, showing q is **T**
    - **Example**

Given the initial assertion p: x:=1 and the final assertion q: z:=3, show the partial correctness of the program segment
y = 2
z = x + y

1. Assume p ≡ T  (x = 1) T
2. Substitue p to the program

(x = 1) {y = 2, z = x +y} (z = 3?)

          z = 1 + 2
          z = 3
          
     Therefore Partially Correct

Different types of *Hoare Triple*: (Rules of inference)

p{S1}q

q{S2}r

:. p{S1;S2}r

- Conditional Statements
    - 1. p ∧ (condition) {S} q, where p & (condition) ≡ T
    - 2. p ∧ ¬(condition) → q, where p ≡ T, and ¬(condition) should be True
    - **Example:**
   
I was absent when my proffesor teach lessons about Power Series, Sets and its Operations. So I would try to learn and study them as best as I could it order for me to get them. Also, the learnings stated about it will have less content compared to the other lessons I have learned having more contents. So I'll try my best to learned from tell as I go on typing them here.

**Power Series**

- Where a0, a1, a2, . . . is a given sequence of constants, and x is a real variable
- Can be thought of as a function of x that is defined inside the interval of convergence. Not all functions can be expressed as power series, but most common and useful functions can.

AND THATS IT! IT'S THE END OF QUIZ ONE TOPICS. Recursion/Induction in now the next topic for Quiz two and I need to review ALL of this before **FEB 19, 2016**.

Introduction to **Sets**

- A *set* is an unordered collection of distinct objects, which may be anything(including other sets).
- {a, b, c} = {b, a, c} = {a, a, b, b, b, c}

- **Empty Set**
    - The *empty set* contains no elements
    - {} or ∅ (Note: {} is not equal to {∅})

- **Membership** - a ∈ {a, b, c, d}
   
- **Set Builder Notation**
    - {x|some property x satisfies}
     - The set of all x/where/ **"**
    - Examples:
       - {r|r ∈ ℝ and r<137}
       - {n|n is an even natural number}
       - {S|S is a set of US currency}
       - {a|a is cute animal}

- **Venn Diagrams**
    - Union - A ∪ B
    - Intersection - A ∩ B
    - Difference (Complementary) - A-B, A\B, B'
    - Symmetric Difference - A △ B

- **Set Identities**
    - Identity Law
    - Domination Law
    - Idempotent Law
    - Complementation Law (Double Negation)
    - Commutative Law
    - Associative Law
    - Distributive Law
    - De Morgan's Law
    - Absorbtion Law
    - Complement Law (Negation)

 - **Subsets**
    - A set S is a subset of a set T (denoted S ⊆ T) if all elements of S are also elements of T.
    - Examples:
       - {1, 2, 3} ⊆ {1, 2, 3, 4}
       - ℕ ⊆ ℤ (every natural number is an integer)
       - ℤ ⊆ ℝ (every integer is a real number)

 - **Power Set** - ℘(S), P(S), ℙ(S) = {*T*|*T* ⊆ S}

##WEEK 6:

This week, we have some sort of continuation to Sets lessons, which is called Cardinality, and a new topic about Functions.

**Cardinality**
 - The number of elements it contains
 - If S is a set, we denote its cardinality by writing |S|
 - Examples:
   - |{a, b, c, d, e}| = 5
   - |{{a, b}, {c, d, e, f, g}, {h}}| = 3
   - |{1, 2, 3, 3, 3}| = 3
   - |{n ∈ N| n < 137}| = 137 (Zero is counted)
   
   - |N| = ℵ₀ (Aleph-zero, aleph-naught, "infinity")
   - |Even| = ℵ₀
   - |ℤ| = ℵ₀

**Function**
 - Let A & B be sets. A function f from A to B is an assignment of **exactly one** element of B to each element of A
 - We write f: A → B or f: A to B (Note: **to** is not an implication)
    - A for domain
    - B for Co-Domain (Can be called as **Range** when a particular subset B is connected from set A)
 - Image:
 
 - Examples:

f(x) = x^2 (Domain
x ∈ ℤ
f: ℤ to ℤ+ (Co-domain; not shown)
"Perfect Square" (Range; not shown)

int floor (float x) {
  }
Domain: float x (float → ℝ) ℝ
Range: int floor (int → ℤ) ℤ

 - Types of Function:
    - One-to-One (Injective) - ∀x∀y(f(x)=f(y) → x=y) and ∀x∀y(x≠y → f(x)≠f(y))
    - Onto (Surjective) Range = Co-domain (and must be filled)
    - One-to-one and Onto (Bijection)

THE SUBMISSION OF THE "PROJECT, 0-0 (Individual)" IS DUE ON **MARCH 1, 2016**

That means I have to install the MIT App Inventor on my computer and use my DLSU Gmail account. The instructions are here: https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/DISMATH_MIT_App_Inventor and here: http://appinventor.mit.edu/explore/ai2/windows.html

####The reference/s used from week 1 until week 6: https://docs.google.com/presentation/d/1OzJWPZaCS3Mugrj9mWqDz2k5C0vxi2xcRftrGBvdfho/edit#slide=id.p

##WEEK 7:

**Algorithm**

 - A finite set of precise instructions for performing a computation or for solving a problem
 - Example - Describe an algorithm for finding the maximum (largest) value in a finite sequence of integers
 
    Procedure: Find Max
    Input: {a1, a2, ..., ai, ..., an}
    Output: maximum, max

          1. max = a1
          2. for i: 2 to n
          3.     if (max < ai)
          4.         max = ai

 - **Preconditions** - Statements that describe valid input
    - Ex: (a1, a2, : : :, an) ∈ ℤ
 - **Postconditions** - Conditions that the ouput should satisfy when the program has run
    - Ex: Output: max is the largest element

 - Properties of Algorithm:
    - Input - An algorithm has input values from a specified set (set for the *Precondition*)
    - Output - From each set of input values an algorithm produces output values from a specified set (set for the *Postcondition*)
    - Definiteness - The steps of an algorithm must be defined precisely
    - Correctness - An algorithm should produce the correct output values for each set of input values
    - Finiteness - An algorithm should produce the desired output after a finite number of steps
    - Generality - The procedure should be applicable for all problems of the desired form, not just for a particular set of input
 
 - **Pseudocode** - A detailed step in the process of developing an algorithm

 - **Searching Algorithms**
    - The problem of locating an element in an ordered list
    - Locate an element x in a list of distinct elements a1, a2,..,an, or determine that is is not in the list
    
    - Types of Searching Algorithms:

 Linear Algorithm

          Procedure: Linear Search
          Input: {a1, a2, ..., ai, ..., an}
                 (x: searched element)
          Output: location, loc
                   {1, ..., n}
                   { = -1 if not found}

           1. loc = -1
           2. for i: 1 to n
           3.     if (x==ai)
           4.         loc = i
           
           OR
          
           1. i = 1
           2. while (i ≤ n ∧ x ≠ y)
           3.        i = i + 1
           4. if (i ≤ n)
           5.     loc = i
           6. else loc = -1

 Binary Algorithm
 
           Procedure: Binary Search
           Input: {a1, a2, ..., ai, ..., an}
                   (x: searched element)
           Output: location, loc
 
           1. i = 1
           2. j = n
           3. while ( i < j) {
           4.        mid = (i + j)/2
           5.        if (x > mid)
           6.            i = mid + 1
           7.        else j = mid }
           8.  if (x==ai)
           9.  loc = i
           10. else loc = -1
 
##WEEK 8:

This is a continuation from the topic we have discussed last week. Here are more examples of the algorithms that are needed to be thoroughly remembered and understand in order to figure out the specific procedures.

 - **Sorting Algorithms** - The algorithm of putting elements in increasing (or decreasing) order

Bubble Sort

          Procedure: Bubble Sort
          Input: {a1, a2, ..., ai, ..., an}
          Output: (x1, x2, ..., xi, ..., xn)
                   x1 < x2 < ... < xn
 
          1. for j: 1 to n-1
          2.   for i: 1 to n-j
          3.       if (ai > ai + 1)
          4.         swap (ai, ai + 1)
          OR basically what it means:
          [temp = ai]
          [ai = ai + 1]
          [ai + 1 = temp]


Insertion Sort

          Procedure: Insertion Sort
          Input: {a1, a2, ..., ai, ..., an}
          Output: (x1, x2, ..., xi, ..., xn)
                   x1 < x2 < ... < xn

          1. for j = 2 to n
          2. {
          3. i = 1
          4.   while aj > ai
          5.     i = i + 1
          6.     m = aj
          7.     for k = 0 to j – i – 1
          8.       aj–k = aj–k–1
          9.      ai = m
          10. }


 - **Greedy Algorithm** - Selects the best choice at each step, instead of considering all sequences of steps that may lead to an optimal solution

Example: Find a change and number of coins for 68 cents.

P, N, P, Q
1, 1, 1, 2

Denomination:

C = { 25, 10, 5, 1}
x = amount

          Procedure: Greedy Algorithm
          Input: C = { 25, 10, 5, 1}, which is {c1, c2, ..., ci, ..., cn}
                 x: amount
          Output: number of coins, n

          1. n = 0
          2. for i: 1 to 4 (or any var)
          3.    while (x ≥ ci)
          4.      x = x - ci
          5.      n = n + 1

Quiz 2: March 18, 2016 (FRI) 1230-1430 HRS. ; Venue: Section EK & EL at AG703; EQ at AG702

####The reference/s used from week 7 until week 8: http://www.slideshare.net/MelvinCabatuan1/dismathpart2


##WEEK 9:

**Graph Theory**

- Graphs - Discrete structures consisting of vertices and edges that connect these vertices.

Example:



 - A graph G = (V, E)  consist of V, a nonempty set of vertices (or nodes), and R, a set of edges. Each edge has either one or two verices associated with it, called its endpoints.
 
Using the example above:

G = (V, E)
V = {L, R, I, O}
E = {(L, R), (L, I), (I, O), (O, R), (I, R)}

Example 2:




G = (V, E)
V = {L, R, I, *G*}
E = {...} ( G is not connected therefore not included in the edges)

Basic Terminology:

 - The degree of a vertex in an udirected graph is the number of edges incident with it, except that a loop at a vertex contributes twice to the degree of that vertex.

Handshaking Theorem:

 - Let G = (V, E) be an undirected graph with e edges, then
    - 2e = ∑deg(v), where
        - v = vertices
        - deg = degrees of the vertices
        - e = edges

Example: How many edges are there in the graph with 10 vertices each of degree six?

          2e = ∑deg(v)
          2e = 6(10)
          2e = 60
          e = 30
       There are total of 30 edges in the graph with 10 vertices with a degree of 6 each.


- A subgraph of a graph G = (V, E) is a graph H = (W, F), where W ⊆ V and F ⊆ E. A subgraph H of G is a proper subgraph of G if H ≠ G.
- Example: 

G1 subgraph G

G = {V, E}
G1 = {G1, E1}

V1 ⊆ V
E1 ⊆ E

V1 = {G, J}
E1 = {(G, J), (J,G)}

- The Union of the two simple graphs G1 = (V1, E1) and G2 = (V2, E2) is the simple graph with the vertex set V1 ∪ V2 and the edge set E1 ∪ E2.



- The Intersection of the two simple graphs G1 = (V1, E1) and G2 = (V2, E2) is the simple graph with the vertex set V1 ∩ V2 and the edge set E1 ∩ E2.



**Paths(Route)**

- A path is a sequence of edges the begins on one vertex.

Euler Circuit and Paths:

- Euler Circuit
    - Covers all the **edges** by crossing the path once and only once; begins and ends with the same vertex.
    - All vetices(nodes) have **even** degrees.
- Euler Path
    - Covers all the **edges** by crossing the path once and only once; starts at one vertex but ends on a different vertex.
    - **Exactly two** vertices(nodes) have **odd** degrees.

Examples:

G1 = Euler Path
G2 = Euler Path
G3 = None

Hamilton Paths and Circuits:

- Hamilton Circuit
    - Covers all the **vertices** by crossing the path once and only once; begins and ends with the same vertex.
    - (It is usually found on closed circuits)
- Hamilton Path
    - Covers all the **vertices** by crossing the path once and only once; starts at one vertex but ends on a different vertex.
    - (It is possible if the circuit is open; it can have a pendant)

**Matrices of Graphs**

ai = 
- **1** if (vi, vj) has a connection
- **0** if otherwise

Example:




Matrix

0 1 1 1
1 0 1 0
1 1 0 0
1 0 0 0

**Isomorphism of Graphs** 

- Graph G = Graph H
- If and only if V1 = V2 and E1 = E2 by connection or pinpointing the location each of the vertices
- They should have the same number of vertices and edges

Example:





G = H
U1 <=> V1
U2 <=> V4
U3 <=> V3
U4 <=> V2


**Planar Graphs**

(Untangle the rope)

- No edges and vertices should cross or intersect
- The **tangles** can be removed

- Kuratowski's Theorem:
    - The graph is non-planar if the subgraph of the graph is K5 or K3,3

**Euler's Formula:**

       r = e - v + 2


##WEEK 10:

Last time on Kuratowski's Theorem...

- Is the Petersen graph shown planar?
    - No
- Is it a K3,3 or K5?
    - K3,3

Techniques to determine the correct subset in Kuratowski's Theorem:

- Technique 1: Compare the degrees of each vertices on both comparing graphs. If they have the same number of degrees, it is most likely that's the subgraph of one of the non-planar graphs (K3,3 when the degrees of each vertices is 3, and K5 when it's 5).
- Technique 2: To check if it is the correct non-planar subgraph, try to delete and compare the similarities by rearranging the vertices. Also, there will be times that there are more vertices, but it can form the figure of the subgraph, thus the graph formed is homeomorphic.


Homeomorphic graph - can be obtained from the same graph by elementary subdivision.
- Elementary Subdivision - remove the necessary vertex between the two vertices that needs to be connected, add the edge that needs to be connected.

**Graph Coloring**

Consider a map (found on the powerpoint)

c(G)= 4 (Chromatic Value)

Euler Circuit - Linear
Chromatic Number - Expenential

    - Technique - Biparite (K3,3) = 2 colors

Four Color Theorem:

- When planar, max color = 4

    - Technique - Kn = n (Parites)
    - Technique - Codd = 3, Ceven = 2 (Circles)
    - Sn = 2 (Stars)
    - Wodd = 3, Weven = 4 (Wheels)

**Trees**

- A tree is connected undirected graph with no simple circuits
- In a proper organized uprooted tree:
    - The topmost part is the root
    - The lowest parts are the children

Why Study Tees

- Binary Search
- Data Transmission and Storage
- Huffman Coding

Examples found the slides (Answers)

- G1
- G2
- G4 (is called *forest*)

A tree is a subset to a connected graph

*Rooted Trees:*

- Internal Vertices - vertices w/ children
- Leaves - vertices w/o children
 
*M-ary Tree:*

- A tree with uniform children
 
*Ordered rooted tree:*

- A rooted tree where the children of each internal vertex are ordered.

Properties of Trees:

- A tree with n vertices has **n - 1** edges.
- A full m-ary tree with i internal vertices contains **n = mi + 1** vertices.
- A full m-ary tree with:
    - **n** vertices has **i = (n - 1)/ m** internal vertices and **l = [(m - 1)n + 1 ]/ m** leaves,
    - **i** internal vertices has **n = mi + 1** vertices and **I = (m - 1)i + 1** leaves,
    - **l** leaves has **n = (ml - 1 )/(m - 1)** vertices and **i = (l - 1 )/(m - 1)** internal vertices.

- Example: (Answers)
    - leaves = l = 100
    - m-ary = m = 4
    - Using the Case III property:
       - n = (399)/(3) = 133 total people seen it
       - i = (99)/(3) = 33 sent the letter

**Modeling Computation**

Given a task, two questions arise.

- Can it be carried out using a computer?
- If yes, how can the task be carried out?

*IBM Deep Blue vs Kasparov**

Types of modeling computation:

- Grammars
- Finite Machine
- Turring Machine
 
*Grammars* 
- are used to generate the words of a language and to determine whether a word is in a language
- formal languages, which are generated by grammars, provide models for both natural languages, such as English, and for programming languages, such as Pascal, Prolog, Co, and Java
- They are extremely important in the construction and theory of compilers

- Compiler - a program that reads a program written in a source language and traslates it into an equivalent program in a target language
 

Syntax vs. Semantics
- The syntax of a natural language is extremely complicated
- In computation, formal language...

Language and Grammars 

- Construct a derivation tree
    - Vocabulary
    - Word
    - Derivation or Parse Tree

Automata Theory:

- Studies the laws of the computation
- Compose of State

- Finite Automation - provides the simpliest model of a computing device
    - Example: Used in Lexical Analyzers
  
        mkcz is a legal name
        69u is not


*Finite-State Machine*

M = (S, I, O, f, g, s0)

S - states (sets)
I - input alphabets (input)
O - output alphabets (ouput)
f - transition function (arrows)
g - output function
s0 - initial states

Examples: (A number of them are in the book)


Reading Assignments: (included in the Final Examination)

- Tree Traversal
- Spanning Trees
- Relations and Their Properties
- n-ary Relations and Applications
- Representing Relations
- Closures of Relations
- Equivalence Relations
- Partial Orderings

####The reference/s used from week 9 until week 10:https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/GraphTheorySlides
(The **Modeling Computation's powerpoint/pdf file is currently unavailable. However, the topic can be found on the referenced book)

###Other Main Resources:

**Required Reading**

- Discrete Mathematics and its Applications. ebook http://www2.fiit.stuba.sk/~kvasnicka/Mathematics%20for%20Informatics/Rosen_Discrete_Mathematics_and_Its_Applications_7th_Edition.pdf
- Stanford, Mathematical Foundations of Computing http://web.stanford.edu/class/cs103/
- MIT, Mathematics for Computer Science http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2005/index.htm

**Interesting Reads:**

- Laurie Abkemeier. Case Study: How I Got the Highest Grade in my Discrete Math Class (http://calnewport.com/blog/2008/11/25/case-study-how-i-got-the-highest-grade-in-my-discrete-math-class/, accessed February 17, 2016)
- David Patrick. Why Discrete Math Is Important. (http://artofproblemsolving.com/articles/discrete-math, accessed February 17, 2016)

**Recommended tutorial videos**

- Introduction to Logic - Definition, Connectives, and Compound Statements. https://www.youtube.com/watch?v=paRt4R71d8s
- Truth tables of logical connectives - Negation (NOT), Conjunction (AND), Disjunction (OR), Conditional (Implication), Biconditional (XNOR), and Exclusive-OR (XOR). https://youtu.be/oKQrt6myHLQ?list=PLDDGPdw7e6Ag1EIznZ-m-qXu4XX3A0cIz
- Logical Equivalence and Proof by Truth Table https://www.youtube.com/watch?v=_xjz99xHH8Q&index=9&list=PLDDGPdw7e6Ag1EIznZ-m-qXu4XX3A0cIz
- Proof using Logic Laws - Identity, Domination, Double Negation, DeMorgan's, Distributive, Absorption, Commutativity, Associativity, and Inverse laws. https://www.youtube.com/watch?v=_xjz99xHH8Q&index=9&list=PLDDGPdw7e6Ag1EIznZ-m-qXu4XX3A0cIz
- Conditionals: Converse, Inverse, and Contrapositive https://www.youtube.com/watch?v=p9VVi90n_48&index=10&list=PLDDGPdw7e6Ag1EIznZ-m-qXu4XX3A0cIz
- Predicate Logic/ Quantificational Logic with Negation https://www.youtube.com/watch?v=XGeIynFIUHs&index=11&list=PLDDGPdw7e6Ag1EIznZ-m-qXu4XX3A0cIz

