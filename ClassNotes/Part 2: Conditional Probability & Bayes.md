# Part 2: Conditional Probability & Bayes

## Conditional Probability

Formula: P(A|B) = P(A ∩ B) / P(B)

Use When: Event B is given.

Interpretation: Restrict the sample space to B and ask how likely A is within that new sample space.

Recognition: Look for words such as "given", "knowing that", "among", or "conditional on".

---

## Multiplication Rule

Formula: P(A ∩ B) = P(A)P(B|A)

Equivalent: P(A ∩ B) = P(B)P(A|B)

Use When: Finding the probability that multiple events occur together.

Recognition: Need the probability of "A and B".

---

## Independence

Definition: Knowing one event occurs does not change the probability of the other.

Key Property: P(A ∩ B) = P(A)P(B)

Equivalent: P(A|B) = P(A)

Equivalent: P(B|A) = P(B)

Recognition: Information about one event has no effect on the other.

---

## Dependence

Definition: Knowing one event occurs changes the probability of the other.

Key Property: P(A ∩ B) = P(A)P(B|A)

Recognition: Events influence each other.

Examples:
- Drawing cards without replacement
- Selecting people from a group
- Quality control sampling

---

## Law of Total Probability

Formula: P(B) = Σ P(B|Ai)P(Ai)

Use When: P(B) is not directly given.

Requirements: A₁, A₂, ..., Aₖ partition the sample space.

Idea: Break the problem into cases and add the probabilities from each case.

Recognition: Multiple groups can produce the same outcome.

Examples:
- Different technicians
- Different factories
- Different machines

---

## Bayes' Theorem

Formula: P(A|B) = P(B|A)P(A) / P(B)

Use When: Need to reverse a conditional probability.

Idea: Update a prior belief after observing new information.

Recognition: Find the probability of a cause after observing an effect.

Examples:
- Medical testing
- Defective products
- Technician repair problems

---

## Bayes Workflow

Step 1: Identify the event you want in the numerator.

Step 2: Calculate P(B) using the Law of Total Probability if necessary.

Step 3: Apply Bayes' Theorem.

Common Pattern:

Need: P(Cause | Evidence)

Given: P(Evidence | Cause)

→ Use Bayes.

---

## Tree Diagrams

Use When: Events occur in stages.

Rules:
- Multiply along a path.
- Add across paths.

Path Probability: P(A ∩ B) = P(A)P(B|A)

Benefit: Makes conditional probability problems easier to visualize.

---

# Problem Recognition Guide

Given another event? → Conditional Probability

Need probability of "A and B"? → Multiplication Rule

Need P(B)? → Law of Total Probability

Need reverse conditional probability? → Bayes' Theorem

Events do not affect each other? → Independence

Events affect each other? → Dependence

Multiple stages? → Tree Diagram

---

# Common Mistakes

Mistake: Using Bayes when P(B) is already known and Conditional Probability is enough.

Mistake: Forgetting to calculate P(B) before applying Bayes.

Mistake: Assuming events are independent without verification.

Mistake: Multiplying probabilities directly when events are dependent.

Mistake: Adding probabilities along a path instead of multiplying.

---

# Reminders

- Independence ⇒ P(A|B) = P(A).
- Dependence ⇒ Conditional probabilities matter.
- Bayes often requires the Law of Total Probability first.
- Tree diagrams are a visualization tool, not a new formula.
- Along a path multiply, across paths add.
