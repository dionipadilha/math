
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

---
### Apply it to the given integrals:

1. $\int x cos(x) dx$
2. $\int x sin(x) dx$
3. $\int log(x) dx$
4. $\int e^x sin(x) dx$
5. $\int x^2 e^x dx$

---
1. $\int x \cos(x) \quad dx$

$$\begin{align*}
u = x \quad &\Rightarrow \quad du = dx\\
dv = \cos(x)  dx \quad &\Rightarrow \quad v = \int \cos(x)  dx = \sin(x)
\end{align*}$$

$$\begin{align*}
\int x \cos(x)  dx &= x \sin(x) - \int \sin(x)  dx\\
&= x \sin(x) + \cos(x) + C
\end{align*}$$

---
2. $\int x \sin(x) dx$

$$\begin{align*}
u = x \quad &\Rightarrow \quad du = dx\\
dv = \sin(x)  dx \quad &\Rightarrow \quad v = \int \sin(x)  dx = -\cos(x)
\end{align*}$$

$$\begin{align*}
\int x \sin(x)  dx &= x (-\cos(x)) - \int (-\cos(x))  dx\\
&= -x \cos(x) + \int \cos(x) dx\\
&= -x \cos(x) + \sin(x) + C
\end{align*}$$

---
3. $\int \log(x)  dx$

$$\begin{align*}
u = \log(x) \quad &\Rightarrow \quad du = \frac{1}{x}  dx\\
dv = dx \quad &\Rightarrow \quad v = x
\end{align*}$$

$$\begin{align*}
\int \log(x)  dx &= x \log(x) - \int x \cdot \frac{1}{x}  dx\\
&= x \log(x) - \int dx\\
&= x \log(x) - x + C
\end{align*}$$

---
4. $\int x^2 e^x  dx$

$$\begin{align*}
u = x^2 \quad &\Rightarrow \quad du = 2x  dx\\
dv = e^x  dx \quad &\Rightarrow \quad v = e^x\\
\int x^2 e^x  dx &= x^2 e^x - \int 2x e^x  dx \quad [a]
\end{align*}$$

$$\begin{align*}
\text{Solving the integrate from [a]:} &\int 2x e^x  dx\\
u = 2x \quad &\Rightarrow \quad du = 2  dx\\
dv = e^x  dx \quad &\Rightarrow \quad v = e^x\\
\int 2x e^x  dx &= 2x e^x - \int 2 e^x  dx \\
&= 2x e^x - 2 e^x \quad [b]
\end{align*}$$

$$\begin{align*}
\text{Replacing [b] in [a]:} \int x^2 e^x  dx &= x^2 e^x - \left( 2x e^x - 2 e^x \right)\\
&= x^2 e^x - 2x e^x + 2 e^x\\
&= 2x e^x - 2 e^x\\
&= 2e^x \left( x  - 1\right)
\end{align*}$$

$$\begin{align*}
\text{Result of the integration:} \int x^2 e^x  dx =2e^x \left( x  - 1\right) + C
\end{align*}$$

---
5. $\int e^x \sin(x)  dx$

$$\begin{align*}
u = \sin(x) \quad &\Rightarrow \quad du = \cos(x)  dx\\
dv = e^x  dx \quad &\Rightarrow \quad v = \int e^x  dx = e^x\\
\int e^x \sin(x) \, dx &= e^x \sin(x) - \int e^x \cos(x)  dx \quad [a]
\end{align*}$$

$$\begin{align*}
\text{Solving the integrate from [a]:} &\int e^x \cos(x)  dx\\
u = \cos(x) \quad &\Rightarrow \quad du = -\sin(x)  dx\\
dv = e^x  dx \quad &\Rightarrow \quad v = \int e^x  dx = e^x\\
\int e^x \cos(x)  dx &= e^x \cos(x) - \int (-e^x \sin(x))  dx\\
&= e^x \cos(x) + \int e^x \sin(x)  dx \quad [b]
\end{align*}$$

$$\begin{align*}
\text{Replacing [b] in [a]:}\int e^x \sin(x)  dx &= e^x \sin(x) - \left( e^x \cos(x) + \int e^x \sin(x)  dx \right)\\
\int e^x \sin(x)  dx &= e^x \sin(x) - e^x \cos(x) - \int e^x \sin(x)  dx\\
2 \int e^x \sin(x) dx &= e^x (\sin(x) - \cos(x))\\
\int e^x \sin(x) dx &= \frac{e^x (\sin(x) - \cos(x))}{2}
\end{align*}$$

$$\begin{align*}
\text{Result of the integration:} \int e^x \sin(x) dx &= \frac{e^x (\sin(x) - \cos(x))}{2} + C
\end{align*}$$
