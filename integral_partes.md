
# Integração por Partes  
  
## Integração por Partes  
  
A integração por partes é uma técnica para resolver integrais de produtos de funções, permitindo transformar a integral original em uma forma mais simples.  
  
A fórmula geral da integração por partes é dada por:  
  
$$\int u \ dv = uv - \int v \ du$$  
  
onde $u$ e $v$ são funções diferenciáveis em relação à variável de integração e $du$ e $dv$ são as suas respectivas diferenciais.  
  
Para aplicar a integração por partes:  
  
1. Escolher $u$ e $dv$ apropriados.  
2. Calcular $du$ e $v$.  
3. Substituir os termos na fórmula geral da integração por partes.  
4. Simplificar a integral resultante.  
5. Resolver a nova integral obtida.  
6. Caso necessário, repita o processo de integração por partes para simplificar ainda mais a integral.  
  
Diretrizes para escolher funções adequadas para $u$ e $dv$:  
I: Funções Inversas trigonométricas ($\sin^{-1}(x)$, $\cos^{-1}(x)$, etc.)  
L: Funções Logarítmicas ($\ln(x)$)  
A: Funções Algébricas (polinomiais como $x^2$, $3x^3$, etc.)  
T: Funções Trigonométricas ($\sin(x)$, $\cos(x)$, etc.)  
E: Funções Exponenciais ($e^x$, $a^x$, etc.)  
  
## Exemplos  
  
### 1. Calcular a integral $\int x \ln(x) \ dx$ :

Calculando os termos apropriados, temos:  

$$
\begin{align*}  
u = \ln(x) &\longrightarrow du = \frac{1}{x} \ dx \\  
dv = x \ dx &\longrightarrow v = \int x \ dx = \frac{x^2}{2}  
\end{align*}  
$$

Aplicando a fórmula de integração por partes, temos:

$$
\begin{align*}
\int x \ln(x) \ dx &= \frac{x^2 \ln(x)}{2} - \int \frac{x^2}{2x} \ dx \\ \\
&=\frac{x^2 \ln(x)}{2} - \frac{1}{2} \int x \ dx \\ \\
&=\frac{x^2 \ln(x)}{2} - \frac{x^2}{4} +C
\end{align*}  
$$  
  
Simplificando a expressão:  
  
$$  
\frac{x^2 \ln(x)}{2} - \frac{x^2}{4} =\ldots
$$  
  
Portanto:  
  
$$\int x \ln(x) \ dx =\frac{x^2(2 \ln(x)-1)}{4} + C$$  
  
---  
  
### 2. Calcular a integral $\int e^x \sin(x) \ dx$:  
  
Calculando os termos apropriados, temos:  
  
$$  
\begin{align*}  
u = \sin(x) &\longrightarrow du = \cos(x) \ dx \\  
dv = e^x \ dx &\longrightarrow v = \int e^x \ dx = e^x  
\end{align*}  
$$  
  
Aplicando a fórmula de integração por partes, temos:  
  
$$\int e^x \sin(x) \ dx = e^x \sin(x) - \int e^x \cos(x) \ dx$$  
  
Neste caso, a integral $\int e^x \cos(x) \ dx$ pode ser resolvida novamente usando integração por partes:  
  
$$  
\begin{align*}  
u = \cos(x) &\longrightarrow du = -\sin(x) \ dx \\  
dv = e^x \ dx &\longrightarrow v = \int e^x \ dx = e^x  
\end{align*}  
$$  
  
$$  
\begin{align*}  
\int e^x \cos(x) \ dx &= e^x \cos(x) - \int e^x (-\sin(x)) \ dx \\  
&= e^x \cos(x) + \int e^x \sin(x) \ dx  
\end{align*}  
$$  
  
Substituindo essa expressão na integral original, temos:  
  
$$  
\begin{align*}  
\int e^x \sin(x) \ dx &= e^x \sin(x) - \left(e^x \cos(x) + \int e^x \sin(x) \ dx\right) \\  
\int e^x \sin(x) \ dx &= e^x \sin(x) - e^x \cos(x) - \int e^x \sin(x) \ dx\\  
2 \int e^x \sin(x) \ dx &=e^x \sin(x) - e^x \cos(x) \\  
\int e^x \sin(x) \ dx &= \frac{e^x \sin(x) - e^x \cos(x)}{2} + C  
\end{align*}  
$$  
  
Simplificando a expressão:  
  
$$\frac{e^x \sin(x) - e^x \cos(x)}{2} = \ldots$$  
  
Portanto:  
  
$$\int e^x \sin(x) \ dx = \frac{e^x(\sin(x)-\cos(x))}{2} + C$$
