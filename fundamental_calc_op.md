### Quick Reference Guide to Fundamental Calculus

- **Limits**: Limits allow us to understand the behavior of a function as its input approaches a certain value, even if the function is not defined at that point. When calculating limits, ensure the function approaches the value from both sides.

- **Derivatives**: The derivative measures the rate at which a function changes as its input changes. It's the slope of the tangent line to the curve of the function at a given point.

- **Integrals**: Integrals compute the area under the curve of a function over an interval. They serve as the reverse process of differentiation (Fundamental Theorem of Calculus).

Expression| Limit| Derivative| Integral
----------|------|-----------|------------
$$k$$| $$k$$| $$0$$| $$kx + C$$
$$k f$$| $$k \lim f$$ | $$k f'$$ | $$k \int f \, dx$$
$$f \pm g$$  | $$\lim f \pm \lim g$$ | $$f' \pm g'$$| $$\int f \, dx \pm \int g \, dx$$
$$f \cdot g$$| $$\lim f \cdot \lim g$$ | $$f' g + f g'$$ | $$\int u \,dv = u v - \int v \,du$$
$$f \div g$$ | $$\frac{\lim f}{\lim g}$$ | $$\frac{f'g - f g'}{g^2}$$ | $$\text{specific techniques}$$
$$f(g(x))$$ | $$f(\lim_{x \to a} g(x))$$ | $$f'(g(x)) \cdot g'(x)$$ | $$\int f(u) \frac{du}{g'(x)}$$