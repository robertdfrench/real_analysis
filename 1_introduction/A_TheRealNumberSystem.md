
# Properties of the Real Number System
Delving deeper into the Real Number System will provide a solid foundation for
all of real analysis. The real numbers, denoted by \(\mathbb{R}\), include both
the rational numbers (\(\mathbb{Q}\)) and the irrational numbers. The rational
numbers are those that can be expressed as a fraction \(\frac{a}{b}\), where
\(a\) and \(b\) are integers, and \(b \neq 0\). The irrational numbers cannot
be expressed as such fractions; examples include \(\sqrt{2}\), \(\pi\), and
\(e\). Together, these sets form the continuum of real numbers, which can be
thought of as every possible point along an infinitely long line.

The real number system is characterized by several foundational properties divided into three main categories: algebraic properties, order properties, and the completeness property.

## Algebraic Properties

1. **Closure**: For any two real numbers \(a\) and \(b\), both \(a + b\) and \(a \cdot b\) are real numbers.
2. **Associativity**: For all real numbers \(a\), \(b\), and \(c\), we have \(a + (b + c) = (a + b) + c\) and \(a \cdot (b \cdot c) = (a \cdot b) \cdot c\).
3. **Commutativity**: For all real numbers \(a\) and \(b\), \(a + b = b + a\) and \(a \cdot b = b \cdot a\).
4. **Distributivity**: For all real numbers \(a\), \(b\), and \(c\), \(a \cdot (b + c) = a \cdot b + a \cdot c\).
5. **Identity Elements**: There exist two unique real numbers, 0 and 1, such that for any real number \(a\), \(a + 0 = a\) and \(a \cdot 1 = a\).
6. **Inverses**: For every real number \(a\), there exists a real number \(-a\) such that \(a + (-a) = 0\), and for every nonzero real number \(a\), there exists a real number \(1/a\) such that \(a \cdot (1/a) = 1\).

### Order Properties

The real numbers are equipped with a natural order that satisfies the following:

1. **Transitivity**: For all real numbers \(a\), \(b\), and \(c\), if \(a < b\) and \(b < c\), then \(a < c\).
2. **Trichotomy**: For any two real numbers \(a\) and \(b\), exactly one of the following is true: \(a < b\), \(a = b\), or \(a > b\).
3. **Compatibility with Addition and Multiplication**: For all real numbers \(a\), \(b\), and \(c\), if \(a < b\), then \(a + c < b + c\), and if \(a < b\) and \(c > 0\), then \(ac < bc\).

### Completeness Property

The most distinctive feature of the real numbers, as opposed to the rational numbers, is the completeness property. This property ensures that there are no "holes" or "gaps" in the real number line.

- **Completeness Axiom**: Every non-empty set of real numbers that is bounded above has a least upper bound (supremum) in the set of real numbers.

This axiom is crucial for the development of calculus and analysis, as it guarantees the existence of limits and enables the precise definition of concepts like continuity and differentiability.

## Implications of the Completeness Property

The completeness property has profound implications for analysis:

- It allows for the precise definition of irrational numbers, as limits of sequences of rational numbers.
- It underlies the Bolzano-Weierstrass theorem, which states that every bounded sequence of real numbers has a convergent subsequence.
- It is foundational for the Intermediate Value Theorem, which assures that a continuous function that takes on two values will take on any value between them at some point.

These properties and the completeness axiom form the backbone of real analysis, setting the stage for exploring limits, continuity, differentiation, and integration with rigor and precision. Understanding these concepts is fundamental to progressing in real analysis and applying these principles to solve complex mathematical problems.

## Exercises
Certainly! Here are several exercises that reinforce the concepts from the introduction to the real number system. These exercises range from foundational proofs to applications of the properties of real numbers.

### Exercise Set

1. **Rational Numbers and Their Properties**
   - **Exercise 1.1**: Prove that the product of two rational numbers is rational.
   - **Exercise 1.2**: Show that the additive inverse of a rational number is rational.

2. **Irrational Numbers**
   - **Exercise 2.1**: Prove that the sum of a rational number and an irrational number is irrational.
   - **Exercise 2.2**: Show that the product of a non-zero rational number and an irrational number is irrational.

3. **Order Properties**
   - **Exercise 3.1**: Suppose \(a\), \(b\), and \(c\) are real numbers. Prove that if \(a < b\), then \(a + c < b + c\).
   - **Exercise 3.2**: Prove that if \(0 < a < b\), then \(a^2 < b^2\). Is the converse true? Justify your answer.

4. **Completeness Property**
   - **Exercise 4.1**: Let \(S\) be a non-empty set of real numbers that is bounded above and let \(B\) be the set of all upper bounds of \(S\). Prove that \(\inf B = \sup S\).
   - **Exercise 4.2**: Consider a non-empty set \(A\) of real numbers that is bounded below. Prove that \(A\) has a greatest lower bound (infimum) in the set of real numbers.

5. **Application and Theoretical Understanding**
   - **Exercise 5.1**: Given that \(\sqrt{2}\) is irrational, prove that \(\sqrt{2} + 1\) is irrational.
   - **Exercise 5.2**: Prove or disprove: The square root of any prime number is irrational.

These exercises require a mix of direct proof, proof by contradiction, and application of the properties and axioms defining the real numbers. They'll help solidify your understanding of the real number system, rational and irrational numbers, and the foundational properties that real numbers possess. If you need hints or solutions for any of these exercises, feel free to ask!

