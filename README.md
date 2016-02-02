# dismathportfolio-Green-Dream-Giant
dismathportfolio-Green-Dream-Giant created by Classroom for GitHub

This portfolio is owned by Mikhael Willard R. Songco



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

Okay, this week he added a new method of proof and another topic that includes proving and other previous subjects.

- Proof by Equivalence - To prove the biconditional statement premise, both P → Q and Q → P must be **TRUE** by using other proving methods.

- **Mathematical Induction** - *Substitution (Basis Step)* + *Direct Proof (Inductive Step)*
    - 1. Basis Step: P(0) or P(1) is shown to be True
    - 2. Inductive Step: Use Direct Proof in order to justify P(0) or P(1)
