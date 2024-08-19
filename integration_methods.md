### Common Integration Methods

Each integration method is tailored for specific types of integrals, and understanding when to apply each one is essential for solving integrals efficiently.

- **Substitution Method**:
This method is useful when the integrand can be rewritten as a function of another variable and its derivative.

$$\int 2x \cdot e^{x^2} \, dx = e^{x^2} + C$$

- **Integration by Parts**:
This method is effective when the integrand is a product of two functions, where one can be easily differentiated and the other easily integrated.

$$\int x e^x \, dx = e^x (x - 1) + C$$

- **Partial Fractions**:
This technique is employed to integrate rational functions by decomposing them into simpler fractions, which can be integrated individually.

$$\int \frac{2x}{x+3} \,dx = 2 \ln|x+3| + C$$ 

$$\int \frac{3x + 5}{(x+1)(x+2)} \, dx = 2 \ln|x+1| + \ln|x+2| + C$$ 

- **Trigonometric Integrals**:
This technique is used when the integrand involves trigonometric functions.

$$\int \sin^2(x) \, dx = \int \frac{1-cos(2x)}{2} \,dx = \frac{x}{2} - \frac{1}{4} \sin(2x) +C$$

- **Trigonometric Substitution**:
This technique is useful when dealing with integrands that involve expressions like $\sqrt{a^2 - x^2}$, $\sqrt{a^2 + x^2}$, or $\sqrt{x^2 - a^2}$. The substitution simplifies the integral into a trigonometric form, which can then be solved using trigonometric identities.

$$\int \frac{dx}{\sqrt{a^2 - x^2}} = \arcsin(\frac{x}{a}) + C$$