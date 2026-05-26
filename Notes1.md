# Probability Notes

## Conditional Probability

\[
P(A|B) = \frac{P(A \cap B)}{P(B)}
\]

Use when event **B is given**.

---

## Law of Total Probability

If \(A_1, A_2, ..., A_k\) partition the sample space:

\[
P(B) = \sum_{i=1}^{k} P(B|A_i)P(A_i)
\]

Use to find \(P(B)\) when it is not directly given.

---

## Bayes' Theorem

\[
P(A|B) = \frac{P(B|A)P(A)}{P(B)}
\]

Workflow:
1. Find \(P(B)\) using Total Probability.
2. Apply Bayes' Theorem.

---

## Independence vs Dependence

### Independent

\[
P(A \cap B) = P(A)P(B)
\]

Equivalent:

\[
P(A|B) = P(A)
\]

\[
P(B|A) = P(B)
\]

### Dependent

\[
P(A \cap B) = P(A)P(B|A)
\]

\[
P(A|B) = \frac{P(A \cap B)}{P(B)}
\]

---

# Probability Models

## Sample Space

\[
\Omega
\]

Set of all possible outcomes.

---

## Union Rule

Two events:

\[
P(A \cup B)=P(A)+P(B)-P(A \cap B)
\]

Three events:

\[
P(A\cup B\cup C)
\]

= sum of singles

− sum of pairwise intersections

+ triple intersection

---

# Counting Techniques

## 1. Multiplication Principle

If a process has \(n_1,n_2,\dots,n_k\) choices:

\[
n_1n_2\cdots n_k
\]

Use for sequential decisions.

---

## 2. Permutations (Order Matters)

Arrange \(r\) objects from \(n\) objects:

\[
{}_nP_r=\frac{n!}{(n-r)!}
\]

Special case:

\[
{}_nP_n=n!
\]

Use when **order matters**.

---

## 3. Combinations (Order Doesn't Matter)

Choose \(r\) objects from \(n\) objects:

\[
{}_nC_r=\frac{n!}{r!(n-r)!}
\]

Use when **order does not matter**.

---

## 4. Multinomial Coefficient

When objects repeat:

\[
\frac{n!}{n_1!n_2!\cdots n_k!}
\]

where

\[
n_1+n_2+\cdots+n_k=n
\]

Example: Arrangements of letters in a word with repeated letters.

---

## 5. Hypergeometric Probability

Population:

- Total: \(N\)
- Successes: \(n_1\)
- Failures: \(n_2\)

Sample size: \(r\)

Probability of getting \(r_1\) successes:

\[
\frac{\binom{n_1}{r_1}\binom{n_2}{r_2}}
{\binom{N}{r}}
\]

where

\[
N=n_1+n_2,\quad r=r_1+r_2
\]

Use for **sampling without replacement**.

---

# Quick Reminders

- If \(P(B)\) is missing → use Total Probability.
- If \(P(B)\) is known → Conditional Probability may be enough.
- Bayes = reverse conditional probability.
- Independence ⇒ conditioning does not change probability.
- Permutation = order matters.
- Combination = order doesn't matter.
- Multinomial = repeated objects.
- Don't forget:

\[
0! = 1
\]
