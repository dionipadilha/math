### Integrals by Parts

Integration by parts is a technique used to solve integrals involving products of functions. The formula is:

$$\int u dv = u v − \int v du$$
where $u$ and $v$ are differentiable functions of $x$.

This formula helps us to transform an integral into a potentially simpler form. It’s important to choose u and dv wisely to simplify the resulting integrals as much as possible. Here’s how to apply it:

1. Find the $u$ and $du$:
- Select $u$ as a part of the integrand that can be differentiated easily.
- Differentiate $u$ to find $du$.

2. Find the $dv$ and $v$:
- Let $dv$ be the part of the integrand which can be integrated easily.
- Integrate $dv$ to find $v$.

3. Evaluate the integration:
- Substitute into the integration by parts formula.
- Simplify the resulting integral.

Apply it to the given integrals:

1. $\int x cos(x) dx$
2. $\int x sin(x) dx$
3. $\int log(x) dx$
4. $\int e^x sin(x) dx$
5. $\int x^2 e^x dx$

---
Let's apply integration by parts to each of the given integrals step by step.

### 1. $\int x \cos(x) \, dx$

For this integral, we can choose:
$$u = x \quad \Rightarrow \quad du = dx$$
$$dv = \cos(x) \, dx \quad \Rightarrow \quad v = \int \cos(x) \, dx = \sin(x)$$

Now, apply the integration by parts formula:
$$
\int x \cos(x) \, dx = x \sin(x) - \int \sin(x) \, dx = x \sin(x) + \cos(x) + C
$$
where $C$ is the constant of integration.

### 2. $\int x \sin(x) \, dx$

For this integral:
$$u = x \quad \Rightarrow \quad du = dx$$
$$dv = \sin(x) \, dx \quad \Rightarrow \quad v = \int \sin(x) \, dx = -\cos(x)$$

Apply integration by parts:
$$
\int x \sin(x) \, dx = x (-\cos(x)) - \int (-\cos(x)) \, dx = -x \cos(x) + \int \cos(x) \, dx = -x \cos(x) + \sin(x) + C
$$

### 3. $\int \log(x) \, dx$

Choose:
$$u = \log(x) \quad \Rightarrow \quad du = \frac{1}{x} \, dx$$
$$dv = dx \quad \Rightarrow \quad v = x$$

Apply integration by parts:
$$
\int \log(x) \, dx = x \log(x) - \int x \cdot \frac{1}{x} \, dx = x \log(x) - \int dx = x \log(x) - x + C
$$

### 4. $\int e^x \sin(x) \, dx$

Here:
$$u = \sin(x) \quad \Rightarrow \quad du = \cos(x) \, dx$$
$$dv = e^x \, dx \quad \Rightarrow \quad v = e^x$$

Apply integration by parts:
$$
\int e^x \sin(x) \, dx = e^x \sin(x) - \int e^x \cos(x) \, dx
$$

To solve $\int e^x \cos(x) \, dx$, choose:
$$u = \cos(x) \quad \Rightarrow \quad du = -\sin(x) \, dx$$
$$dv = e^x \, dx \quad \Rightarrow \quad v = e^x$$

Apply integration by parts again:
$$
\int e^x \cos(x) \, dx = e^x \cos(x) - \int (-e^x \sin(x)) \, dx = e^x \cos(x) + \int e^x \sin(x) \, dx
$$

Substitute back into the original equation:
$$
\int e^x \sin(x) \, dx = e^x \sin(x) - e^x \cos(x) - \int e^x \sin(x) \, dx
$$
$$2 \int e^x \sin(x) \, dx = e^x (\sin(x) - \cos(x)) + C$$
$$\int e^x \sin(x) \, dx = \frac{e^x (\sin(x) - \cos(x))}{2} + C$$

### 5. $\int x^2 e^x \, dx$

Choose:
$$u = x^2 \quad \Rightarrow \quad du = 2x \, dx$$
$$dv = e^x \, dx \quad \Rightarrow \quad v = e^x$$

Apply integration by parts:
$$
\int x^2 e^x \, dx = x^2 e^x - \int 2x e^x \, dx
$$

For $\int 2x e^x \, dx$:
$$u = 2x \quad \Rightarrow \quad du = 2 \, dx$$
$$dv = e^x \, dx \quad \Rightarrow \quad v = e^x$$

Apply integration by parts:
$$
\int 2x e^x \, dx = 2x e^x - \int 2 e^x \, dx = 2x e^x - 2 e^x + C
$$

Substitute back into the original equation:
$$
\int x^2 e^x \, dx = x^2 e^x - (2x e^x - 2 e^x + C) = x^2 e^x - 2x e^x + 2 e^x + C
$$

Thus, these are the results of applying integration by parts to each of the given integrals.
