# Part 1: Counting and Probability Foundations

## Sample Space

Definition:

Ω = set of all possible outcomes.

Example:

- Roll a die
- Ω = {1, 2, 3, 4, 5, 6}

---
## Complement Rule

Formula: P(Aᶜ) = 1 − P(A)

---

## Union Rule

### Two Events

Formula:

P(A ∪ B) = P(A) + P(B) − P(A ∩ B)

Use when:
- Finding the probability of A or B occurring.

---

### Three Events

Formula:

P(A ∪ B ∪ C) = P(A) + P(B) + P(C) − P(A ∩ B) − P(A ∩ C) − P(B ∩ C) + P(A ∩ B ∩ C)

Idea:
- Add individual probabilities.
- Subtract double-counted overlaps.
- Add back the triple overlap.

---

# Counting Techniques

## 1. Multiplication Principle

Formula:

n₁ × n₂ × ... × nₖ

Use when:
- A process happens in stages.
- Each stage has a fixed number of choices.

Example:

- Outfit = 3 shirts × 2 pants
- Total outcomes = 6

---

## 2. Permutation

Formula:

nPr = n! / (n − r)!

Special Case:

nPn = n!

Use when:
- Order matters.


Recognition:

"Would swapping two objects create a different outcome?"

If YES → Permutation

---

## 3. Combination

Formula:

nCr = n! / [r!(n − r)!]

Use when:
- Order does not matter.

Recognition:

"Would swapping two objects create the same outcome?"

If YES → Combination

---

## 4. Multinomial Coefficient

**Formula:**

n! / (n₁!n₂!...nₖ!)

Constraint:

n₁ + n₂ + ... + nₖ = n

Use when:
- Some objects repeat.
- All objects are arranged.

**Examples:**

TORONTO = 7! / (2!2!2!)

MISSISSIPPI = 11! / (4!4!2!)

**Signal:**

- Repeated letters
- Arrange all letters


---

## 5. With Replacement vs Without Replacement
### With Replacement

Properties:

Events are independent.

P(A ∩ B) = P(A)P(B)

### Without Replacement

Events are dependent.

---

## 6. Hypergeometric Probability

Formula:

[C(n₁,r₁) · C(n₂,r₂)] /   C(N,r)

Where:

N = n₁ + n₂

r = r₁ + r₂

**Signal:**

- Sampling without replacement.


## 7. Circular Permutation

Formula: (n − 1)!

Use When: Objects are arranged around a circle.


Idea:

Rotations are considered the same arrangement.

Example:

Arrange 5 people around a round table.

Number of arrangements:

(5 − 1)! = 4!= 24


---

# Quick Reminders

- Permutation = order matters.
- Combination = order doesn't matter.
- Multinomial = repeated objects.
- Hypergeometric = without replacement.
- Always identify the pattern before choosing a formula.

Don't forget:

0! = 1
