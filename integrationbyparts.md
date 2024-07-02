### Integration by Parts

Find the integral $\int x^2 e^x \, dx$.

1. **Choose $u$ and $dv$**:

$$\begin{align*}
u = x^2 \quad &\Rightarrow \quad du = 2x \, dx\\
dv = e^x \, dx \quad &\Rightarrow \quad v = e^x 
\end{align*}$$

2. **Apply Formula**:

$$\begin{align*}
\int u \, dv &= uv - \int v \, du\\
\int x^2 e^x \, dx &= x^2 e^x - \int e^x \,2x \, dx\\
&= x^2 e^x - \int 2x\,e^x \, dx
\end{align*}$$


3. **Solve the Remaining Integral**:

$$\begin{align*}
u = 2x \quad &\Rightarrow \quad du = 2 \, dx\\
dv = e^x \, dx \quad &\Rightarrow \quad v = e^x
\end{align*}$$


$$\begin{align*}
\int 2x e^x \, dx
&= 2x e^x - \int 2 e^x \, dx\\
&= 2x e^x - 2e^x
\end{align*}$$

4. **Combine Results**:

$$\begin{align*}
\int x^2 e^x \, dx 
&= x^2 e^x - (2x e^x - 2e^x)\\
&= x^2 e^x - 2x e^x + 2e^x\\
&= e^x (x^2 - 2x + 2)
\end{align*}$$


5. **Therefore**:

$$\int x^2 e^x \, dx = e^x (x^2 - 2x + 2) + C$$.
