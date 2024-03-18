# 1. Introduction to Real Analysis
Let's dive into the first topic: **Introduction to Real Analysis**. This part of the course lays the foundation for everything that follows, so it's crucial to get a solid understanding of these concepts. 

### A. The Real Number System

The real number system \(\mathbb{R}\) is the backbone of real analysis. It consists of all the rational numbers (fractions of integers) and irrational numbers (numbers that cannot be expressed as a fraction of two integers). The real numbers can be visualized as points on an infinitely long line known as the real line, where each point corresponds to a unique real number.

- **Properties of Real Numbers**: Commutative, associative, and distributive laws for addition and multiplication; existence of additive and multiplicative identities (0 and 1, respectively); existence of additive inverses (negative numbers) and multiplicative inverses (reciprocals for nonzero numbers).
- **Order Properties**: The real numbers are ordered, meaning we can compare any two numbers and say one is greater than, less than, or equal to the other. This order is compatible with the algebraic operations (e.g., if \(a < b\), then \(a + c < b + c\) for any \(c\)).

### B. Supremum and Infimum

These concepts are related to the idea of bounds.

- **Upper and Lower Bounds**: A set \(S \subseteq \mathbb{R}\) has an upper bound if there is some real number \(M\) such that \(s \leq M\) for all \(s \in S\). Similarly, \(S\) has a lower bound if there is some number \(m\) such that \(m \leq s\) for all \(s \in S\).
- **Supremum (Least Upper Bound)**: The supremum (denoted as \(\sup S\)) of a set \(S\) is the smallest real number that is an upper bound of \(S\).
- **Infimum (Greatest Lower Bound)**: The infimum (denoted as \(\inf S\)) of a set \(S\) is the largest real number that is a lower bound of \(S\).

### C. Sequences and Series of Real Numbers

A sequence is a list of numbers written in a definite order. A series is the sum of the terms of a sequence.

- **Convergence of Sequences**: A sequence \((a_n)\) converges to a real number \(L\) if, for every positive number \(\epsilon\), there exists an integer \(N\) such that \(|a_n - L| < \epsilon\) for all \(n > N\).
- **Series and Convergence**: A series \(\sum a_n\) converges if the sequence of its partial sums converges.

## Exercises
To start, we'll focus on **The Real Number System**. Here are some points to ponder and exercises to get you started:

### Exercise 1
Prove that the sum of any two rational numbers is rational

**Proof:**

Recall that a rational number is defined as a number that can be expressed as the fraction \(\frac{a}{b}\), where \(a\) and \(b\) are integers and \(b \neq 0\).

Let's take two rational numbers, \(\frac{a}{b}\) and \(\frac{c}{d}\), where \(a, b, c,\) and \(d\) are integers and \(b, d \neq 0\).

The sum of these two rational numbers is:

\[
\frac{a}{b} + \frac{c}{d} = \frac{ad + bc}{bd}
\]

Since the product and sum of integers are integers (integers are closed under multiplication and addition), \(ad + bc\) and \(bd\) are both integers. Moreover, \(bd \neq 0\) because neither \(b\) nor \(d\) is zero (the product of two non-zero integers is a non-zero integer).

Therefore, the sum \(\frac{ad + bc}{bd}\) is a ratio of two integers with a non-zero denominator, which means it is a rational number. This demonstrates that the sum of any two rational numbers is rational.


### Exercise 2
Show that the square root of 2 is irrational.
