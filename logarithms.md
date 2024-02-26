## Logarithms

### Introduction

Logarithms are the inverse of exponentiation. They answer the question: "To what power must we raise a number (the base) to get another number (the argument)?" Understanding logarithms is crucial in various fields, including mathematics, science, engineering, and finance.

### Main Idea

In simplest terms, logarithms are a way of expressing repeated multiplication. Instead of writing out `b x b x b...n times`, we can use `log_b(x)` to represent the exponent `n` to which the base `b` needs to be raised to get the argument `x`.

### Key Concepts

* **Base (b)**: The positive constant number we raise to the power in the logarithmic expression. The most common bases are 10 (common logarithms) and e (natural logarithms).
* **Argument (x)**: The number we want to find the exponent for.
* **Exponent (n)**: The value representing "how many times" the base must be multiplied by itself to reach the argument. In logarithmic terms, it's represented by `log_b(x)`.

### Key Formula and Explanation

One of the essential formulas in logarithms is the **change of base rule**:

$$log_a(x) = \frac{\log_b(x)}{\log_b(a)}$$

* This formula allows us to convert logarithms from one base to another.
* `a` and `b` are any positive constants where `a ≠ 1` and `b ≠ 1`.
* `x` is the positive argument.

**Explanation:**

* This formula essentially says that the logarithm of `x` to base `a` is equal to the logarithm of `x` to base `b` divided by the logarithm of `a` to base `b`.

### Demonstration Example

**Problem:** Find the value of `log_5(25)` using the change of base rule, given that `log_3(25) = 2`.

**Solution:**

1. Apply the change of base rule with `a = 5` and `b = 3`:

$$log_5(25) = \frac{\log_3(25)}{\log_3(5)}$$

2. Substitute the given value:

$$log_5(25) = \frac{2}{\log_3(5)}$$

**Note:** We cannot solve further without the value of `log_3(5)`. This demonstrates the need for logarithm tables or calculators when working with specific bases.

### Common Pitfalls

* **Forgetting the base:** Always specify the base of the logarithm. Otherwise, the expression is ambiguous.
* **Taking the logarithm of negative numbers:** Logarithms are undefined for negative arguments and non-positive bases.
* **Mixing up multiplication and addition:** Remember, logarithms are the inverse of exponentiation, not multiplication. Therefore, `log(a x b)` is not the same as `log(a) + log(b)`.

### Limitations

* Logarithms are undefined for negative arguments and non-positive bases.
* Solving logarithmic equations can sometimes be complex and require numerical methods.

### Extensions

* Explore logarithmic properties like product rule, quotient rule, and power rule.
* Learn about the applications of logarithms in various fields, such as compound interest calculations, signal processing, and population growth models.

### Resources

* Khan Academy: [https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:logs](https://www.khanacademy.org/math/algebra2/x2ec2f6f830c9fb89:logs)
* Math is Fun: [https://www.britannica.com/science/logarithm](https://www.britannica.com/science/logarithm)
* Brilliant: [https://brilliant.org/wiki/logarithms/](https://brilliant.org/wiki/logarithms/)

### Next

* Explore the properties of logarithms in more detail.
* Apply logarithms to solve real-world problems.
