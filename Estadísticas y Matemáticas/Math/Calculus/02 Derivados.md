# Cálculo básico

# Derivadas

La derivada de una función mide cómo cambia el valor de la función con respecto a un cambio en su variable independiente. En términos más simples, la derivada nos dice la pendiente de la tangente a la curva de la función en un punto dado.

## Definición de derivada

La derivada de una función $f(x)$ en un punto $x$ se define como el límite del cociente de incrementos cuando el incremento tiende a cero:

$$f'(x) = \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}$$

Esto significa que la derivada nos da la tasa de cambio instantánea de la función en el punto $x$.

## Notación de la derivada

La derivada se puede denotar de varias maneras, entre las cuales las más comunes son:

- $f'(x)$: Notación de Lagrange.

- $\frac{dy}{dx}$: Notación de Leibniz.

- $Df(x)$: Notación de función derivada.

- $D_x f(x)$: Notación de derivada respecto a $x$.

- $f^{(n)}(x)$: Notación para la $n$-ésima derivada de $f(x)$.

## Reglas de derivación

Existen varias reglas básicas para calcular derivadas de funciones comunes:

- **Regla de la suma**: La derivada de la suma de dos funciones es la suma de sus derivadas.
$$\frac{d}{dx}(f(x) + g(x)) = f'(x) + g'(x)$$

- **Regla del producto**: La derivada del producto de dos funciones se calcula usando la regla del producto.
$$\frac{d}{dx}(f(x) \cdot g(x)) = f'(x) \cdot g(x) + f(x) \cdot g'(x)$$

- **Regla del cociente**: La derivada del cociente de dos funciones se calcula usando la regla del cociente.
$$\frac{d}{dx}\left(\frac{f(x)}{g(x)}\right) = \frac{f'(x) \cdot g(x) - f(x) \cdot g'(x)}{(g(x))^2}$$

- **Regla de la cadena**: La derivada de una función compuesta se calcula usando la regla de la cadena.
$$\frac{d}{dx}(f(g(x))) = f'(g(x)) \cdot g'(x)$$

- **Derivadas de funciones comunes**:

  - $\frac{d}{dx}(x^n) = n \cdot x^{n-1}$
  
  - $\frac{d}{dx}(\sin(x)) = \cos(x)$
  
  - $\frac{d}{dx}(\cos(x)) = -\sin(x)$
  
  - $\frac{d}{dx}(\tan(x)) = \sec^2(x)$
  
  - $\frac{d}{dx}(e^x) = e^x$
  
  - $\frac{d}{dx}(\ln(x)) = \frac{1}{x}$

- **Derivadas de funciones trigonométricas**:
  
  - $\frac{d}{dx}(\sin(x)) = \cos(x)$
  
  - $\frac{d}{dx}(\cos(x)) = -\sin(x)$
  
  - $\frac{d}{dx}(\tan(x)) = \sec^2(x)$

- **Derivadas de funciones exponenciales y logarítmicas**:
  
  - $\frac{d}{dx}(e^x) = e^x$
  
  - $\frac{d}{dx}(\ln(x)) = \frac{1}{x}$

- **Derivadas de funciones logarítmicas**:

  - $\frac{d}{dx}(\log_b(x)) = \frac{1}{x \ln(b)}$, donde $b$ es la base del logaritmo.
  
- **Derivadas de funciones hiperbólicas**:
  
  - $\frac{d}{dx}(\sinh(x)) = \cosh(x)$
  
  - $\frac{d}{dx}(\cosh(x)) = \sinh(x)$
  
  - $\frac{d}{dx}(\tanh(x)) = \text{sech}^2(x)$
  
- **Derivadas de funciones inversas**:
  
  - $\frac{d}{dx}(\arcsin(x)) = \frac{1}{\sqrt{1 - x^2}}$
  
  - $\frac{d}{dx}(\arccos(x)) = -\frac{1}{\sqrt{1 - x^2}}$
  
  - $\frac{d}{dx}(\arctan(x)) = \frac{1}{1 + x^2}$
  
- **Derivadas de funciones racionales**:
  
  - $\frac{d}{dx}\left(\frac{1}{x}\right) = -\frac{1}{x^2}$
  
  - $\frac{d}{dx}\left(\frac{1}{x^n}\right) = -\frac{n}{x^{n+1}}$, donde $n$ es un número real.
  
- **Derivadas de funciones compuestas**:
  
  - Si $f(x) = g(h(x))$, entonces la derivada se calcula como:
$$f'(x) = g'(h(x)) \cdot h'(x)$$

- **Derivadas de funciones polinómicas**:
  
  - Si $f(x) = a_n x^n + a_{n-1} x^{n-1} + ... + a_1 x + a_0$, entonces:
$$f'(x) = n a_n x^{n-1} + (n-1) a_{n-1} x^{n-2} + ... + a_1$$

- **Derivadas de funciones exponenciales**:

  - Si $f(x) = a \cdot b^x$, entonces:
$$f'(x) = a \cdot b^x \cdot \ln(b)$$



## Aplicaciones de la derivada

Las derivadas tienen numerosas aplicaciones en matemáticas, física, economía y otras disciplinas. Algunas de las aplicaciones más comunes incluyen:

- **Optimización**: Las derivadas se utilizan para encontrar máximos y mínimos de funciones, lo que es fundamental en problemas de optimización.

- **Tasa de cambio**: Las derivadas permiten calcular la tasa de cambio instantánea de una variable con respecto a otra, como la velocidad en física.

- **Análisis de gráficos**: Las derivadas ayudan a determinar la pendiente de la tangente a una curva en un punto dado, lo que permite analizar el comportamiento de la función.

- **Modelado de fenómenos**: En ciencias e ingeniería, las derivadas se utilizan para modelar fenómenos naturales y sistemas dinámicos.