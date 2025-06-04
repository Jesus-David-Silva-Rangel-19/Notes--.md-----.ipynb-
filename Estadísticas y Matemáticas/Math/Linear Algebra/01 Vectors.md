# **¿Qué es un Vector?**

Un vector es un objeto matemático que tiene tanto una magnitud como una dirección. 

En álgebra lineal, los vectores se representan comúnmente como listas ordenadas de números, que pueden ser visualizados como puntos en un espacio n-dimensional. Por ejemplo, un vector en dos dimensiones puede representarse como $\mathbf{v} = (x, y)$, donde $x$ e $y$ son las coordenadas del vector.

Los vectores pueden sumarse entre sí y multiplicarse por un escalar, lo que permite realizar operaciones como la combinación lineal de vectores. 

Además, los vectores son fundamentales para definir espacios vectoriales, que son conjuntos de vectores que cumplen ciertas propiedades.

## **Ejemplo de un Vector:**

Un vector en tres dimensiones podría ser $\mathbf{v} = (3, -2, 5)$, que representa un punto en el espacio tridimensional con coordenadas $x = 3$, $y = -2$ y $z = 5$.

Otro ejemplo es el vector:

$$
\mathbf{u} = \begin{pmatrix}
1 \\
2 \\
3
\end{pmatrix}
$$

# Operaciones con Vectores

## **Suma de Vectores:**

La suma de dos vectores se realiza sumando sus componentes correspondientes. Por ejemplo, si tenemos los vectores $\mathbf{u} = (u_1, u_2)$ y $\mathbf{v} = (v_1, v_2)$, la suma se define como:

$$
\mathbf{u} + \mathbf{v} = (u_1 + v_1, u_2 + v_2)
$$

Por ejemplo, si $\mathbf{u} = (1, 2)$ y $\mathbf{v} = (3, 4)$, entonces:
$$
\mathbf{u} + \mathbf{v} = (1 + 3, 2 + 4) = (4, 6)
$$
## **Multiplicación por un Escalar:**
La multiplicación de un vector por un escalar se realiza multiplicando cada componente del vector por el escalar. Si $c$ es un escalar y $\mathbf{u} = (u_1, u_2)$, entonces:
$$
c \cdot \mathbf{u} = (c \cdot u_1, c \cdot u_2)
$$
Por ejemplo, si $c = 2$ y $\mathbf{u} = (1, 2)$, entonces:
$$
2 \cdot \mathbf{u} = (2 \cdot 1, 2 \cdot 2) = (2, 4)
$$
## **Producto Punto:**
El producto punto de dos vectores se define como la suma de los productos de sus componentes correspondientes. Si $\mathbf{u} = (u_1, u_2)$ y $\mathbf{v} = (v_1, v_2)$, entonces el producto punto se define como:
$$
\mathbf{u} \cdot \mathbf{v} = u_1 v_1 + u_2 v_2
$$
Por ejemplo, si $\mathbf{u} = (1, 2)$ y $\mathbf{v} = (3, 4)$, entonces:
$$
\mathbf{u} \cdot \mathbf{v} = 1 \cdot 3 + 2 \cdot 4 = 3 + 8 = 11
$$
## **Norma de un Vector:**
La norma de un vector es una medida de su longitud o magnitud. Para un vector $\mathbf{u} = (u_1, u_2)$, la norma se define como:
$$
\|\mathbf{u}\| = \sqrt{u_1^2 + u_2^2}
$$
Por ejemplo, si $\mathbf{u} = (3, 4)$, entonces:
$$
\|\mathbf{u}\| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5
$$
## **Ángulo entre Vectores:**
El ángulo $\theta$ entre dos vectores $\mathbf{u}$ y $\mathbf{v}$ se puede calcular utilizando el producto punto y las normas de los vectores:
$$
\cos(\theta) = \frac{\mathbf{u} \cdot \mathbf{v}}{\|\mathbf{u}\| \|\mathbf{v}\|}
$$
Despejando $\theta$, tenemos:
$$
\theta = \cos^{-1}\left(\frac{\mathbf{u} \cdot \mathbf{v}}{\|\mathbf{u}\| \|\mathbf{v}\|}\right)
$$
Por ejemplo, si $\mathbf{u} = (1, 0)$ y $\mathbf{v} = (0, 1)$, entonces:
$$
\mathbf{u} \cdot \mathbf{v} = 1 \cdot 0 + 0 \cdot 1 = 0
$$
Y las normas son:
$$
\|\mathbf{u}\| = \sqrt{1^2 + 0^2} = 1
$$
$$
\|\mathbf{v}\| = \sqrt{0^2 + 1^2} = 1
$$
Por lo tanto, el ángulo es:
$$
\theta = \cos^{-1}\left(\frac{0}{1 \cdot 1}\right) = \cos^{-1}(0) = \frac{\pi}{2} \text{ radianes} = 90^\circ
$$
## **Proyección de un Vector:**
La proyección de un vector $\mathbf{u}$ sobre otro vector $\mathbf{v}$ se define como:
$$
\text{proj}_{\mathbf{v}} \mathbf{u} = \frac{\mathbf{u} \cdot \mathbf{v}}{\|\mathbf{v}\|^2} \mathbf{v}
$$
Por ejemplo, si $\mathbf{u} = (3, 4)$ y $\mathbf{v} = (1, 0)$, entonces:
$$
\mathbf{u} \cdot \mathbf{v} = 3 \cdot 1 + 4 \cdot 0 = 3
$$
Y la norma de $\mathbf{v}$ es:
$$
\|\mathbf{v}\| = \sqrt{1^2 + 0^2} = 1
$$
Por lo tanto, la proyección es:
$$
\text{proj}_{\mathbf{v}} \mathbf{u} = \frac{3}{1^2} \mathbf{v} = 3 \cdot (1, 0) = (3, 0)
$$
## **Espacios Vectoriales:**
Un espacio vectorial es un conjunto de vectores que cumple con ciertas propiedades, como la cerradura bajo la suma y la multiplicación por escalares. Los espacios vectoriales son fundamentales en álgebra lineal y tienen aplicaciones en diversas áreas de las matemáticas y la física.
## **Base y Dimensión:**
La base de un espacio vectorial es un conjunto de vectores linealmente independientes que generan todo el espacio. La dimensión de un espacio vectorial es el número de vectores en una base del espacio. Por ejemplo, en $\mathbb{R}^2$, la dimensión es 2, y una posible base es $\{(1, 0), (0, 1)\}$.
## **Dependencia e Independencia Lineal:**
La dependencia lineal se refiere a una relación entre vectores en la que al menos uno de los vectores puede expresarse como una combinación lineal de otros. Por otro lado, un conjunto de vectores es linealmente independiente si ninguno de ellos puede expresarse como una combinación lineal de los demás.
## **Transformaciones Lineales:**
Las transformaciones lineales son funciones que mapean vectores de un espacio vectorial a otro, preservando la estructura del espacio. Estas transformaciones pueden representarse mediante matrices y son fundamentales en álgebra lineal.
## **Ejemplo de Transformación Lineal:**
Una transformación lineal común es la rotación de un vector en el plano. Si tenemos un vector $\mathbf{u} = (x, y)$ y queremos rotarlo un ángulo $\theta$, la transformación se puede representar como:

$$\begin{pmatrix}
x' \\
y'
\end{pmatrix} 
= \begin{pmatrix}
\cos(\theta) & -\sin(\theta) \\
\sin(\theta) & \cos(\theta)
\end{pmatrix}
\begin{pmatrix}
x \\
y
\end{pmatrix}
$$
Donde $(x', y')$ son las nuevas coordenadas del vector rotado.
## **Ejemplo de Dependencia Lineal:**
Consideremos los vectores $\mathbf{u} = (1, 2)$ y $\mathbf{v} = (2, 4)$. Podemos ver que $\mathbf{v}$ es un múltiplo escalar de $\mathbf{u}$, ya que $\mathbf{v} = 2 \cdot \mathbf{u}$. Esto significa que los vectores son linealmente dependientes.
## **Ejemplo de Independencia Lineal:**
Consideremos los vectores $\mathbf{u} = (1, 0)$ y $\mathbf{v} = (0, 1)$. No hay forma de expresar uno de estos vectores como una combinación lineal del otro, por lo que son linealmente independientes.
## **Ejemplo de Espacio Vectorial:**
Un ejemplo de espacio vectorial es el conjunto de todos los vectores en $\mathbb{R}^3$. Este espacio incluye todos los vectores de la forma $(x, y, z)$, donde $x$, $y$ y $z$ son números reales. Las operaciones de suma y multiplicación por escalares están definidas en este espacio, lo que lo convierte en un espacio vectorial.
## **Ejemplo de Base y Dimensión:**
Un ejemplo de base en $\mathbb{R}^3$ es el conjunto de vectores $\{(1, 0, 0), (0, 1, 0), (0, 0, 1)\}$. Estos vectores son linealmente independientes y generan todo el espacio $\mathbb{R}^3$. La dimensión de este espacio es 3, ya que hay tres vectores en la base.
## **Ejemplo de Transformación Lineal:**
Una transformación lineal común es la proyección de un vector en el eje $x$. Si tenemos un vector $\mathbf{u} = (x, y)$, la proyección en el eje $x$ se puede representar como:
$$
\text{proj}_{x} \mathbf{u} = (x, 0)
$$
Esto significa que la componente $y$ del vector se elimina, y solo queda la componente $x$.
## **Ejemplo de Producto Cruz:**
El producto cruz de dos vectores en $\mathbb{R}^3$ se define como un vector perpendicular a ambos vectores. Si tenemos los vectores $\mathbf{u} = (u_1, u_2, u_3)$ y $\mathbf{v} = (v_1, v_2, v_3)$, el producto cruz se define como:
$$
\mathbf{u} \times \mathbf{v} = \begin{pmatrix}
u_2 v_3 - u_3 v_2 \\
u_3 v_1 - u_1 v_3 \\
u_1 v_2 - u_2 v_1
\end{pmatrix}
$$
Por ejemplo, si $\mathbf{u} = (1, 0, 0)$ y $\mathbf{v} = (0, 1, 0)$, entonces:
$$
\mathbf{u} \times \mathbf{v} = \begin{pmatrix}
0 \cdot 0 - 0 \cdot 1 \\
0 \cdot 0 - 1 \cdot 0 \\
0 \cdot 1 - 0 \cdot 0
\end{pmatrix}
= \begin{pmatrix}
0 \\
0 \\
0
\end{pmatrix}
$$
Esto significa que el producto cruz de estos dos vectores es el vector nulo, ya que son paralelos.
## **Ejemplo de Producto Escalar:**
El producto escalar de dos vectores en $\mathbb{R}^3$ se define como la suma de los productos de sus componentes correspondientes. Si tenemos los vectores $\mathbf{u} = (u_1, u_2, u_3)$ y $\mathbf{v} = (v_1, v_2, v_3)$, el producto escalar se define como:
$$
\mathbf{u} \cdot \mathbf{v} = u_1 v_1 + u_2 v_2 + u_3 v_3
$$
Por ejemplo, si $\mathbf{u} = (1, 2, 3)$ y $\mathbf{v} = (4, 5, 6)$, entonces:
$$
\mathbf{u} \cdot \mathbf{v} = 1 \cdot 4 + 2 \cdot 5 + 3 \cdot 6 = 4 + 10 + 18 = 32
$$
Esto significa que el producto escalar de estos dos vectores es 32, lo que indica la relación entre ellos en términos de magnitud y dirección.

# **Tipos de Vectores:**
Los vectores pueden clasificarse en diferentes tipos según sus propiedades y características. Algunos de los tipos más comunes son:
## **Vectores nulos:** 
Vectores que tienen una magnitud de cero. Por ejemplo, el vector $\mathbf{0} = (0, 0)$ es un vector nulo en $\mathbb{R}^2$.
## **Vectores unitarios:** 
Vectores que tienen una magnitud de uno. Por ejemplo, el vector $\mathbf{u} = \left(\frac{1}{\sqrt{2}}, \frac{1}{\sqrt{2}}\right)$ es un vector unitario en $\mathbb{R}^2$.   
## **Vectores ortogonales:** 
Vectores que son perpendiculares entre sí. 
Por ejemplo, los vectores $\mathbf{u} = (1, 0)$ y $\mathbf{v} = (0, 1)$ son ortogonales en $\mathbb{R}^2$.
## **Vectores paralelos:** 
Vectores que tienen la misma dirección o son múltiplos escalares entre sí. 
Por ejemplo, los vectores $\mathbf{u} = (2, 4)$ y $\mathbf{v} = (1, 2)$ son paralelos en $\mathbb{R}^2$.
## **Vectores libres:** 
Vectores que no tienen un punto de aplicación fijo y pueden trasladarse en el espacio sin cambiar su dirección o magnitud. 
Por ejemplo, el vector $\mathbf{u} = (1, 2)$ es un vector libre en $\mathbb{R}^2$.
## **Vectores fijos:** 
Vectores que tienen un punto de aplicación fijo en el espacio. 
Por ejemplo, el vector $\mathbf{u} = (1, 2)$ aplicado en el punto $(3, 4)$ es un vector fijo en $\mathbb{R}^2$.
## **Vectores columna:** 
Vectores que se representan como una matriz de una sola columna. 

Por ejemplo, el vector $\mathbf{u} = \begin{pmatrix} 1 \\ 2 \\ 3 \end{pmatrix}$ es un vector columna en $\mathbb{R}^3$.

## **Vectores fila:** 
Vectores que se representan como una matriz de una sola fila. 
Por ejemplo, el vector $\mathbf{u} = \begin{pmatrix} 1 & 2 & 3 \end{pmatrix}$ es un vector fila en $\mathbb{R}^3$.
## **Vectores de posición:** 
Vectores que representan la posición de un punto en el espacio. 
Por ejemplo, el vector $\mathbf{u} = (x, y, z)$ representa la posición del punto $(x, y, z)$ en $\mathbb{R}^3$.
## **Vectores de desplazamiento:** 
Vectores que representan el cambio de posición entre dos puntos. 
Por ejemplo, el vector $\mathbf{u} = (x_2 - x_1, y_2 - y_1)$ representa el desplazamiento entre los puntos $(x_1, y_1)$ y $(x_2, y_2)$ en $\mathbb{R}^2$.
## **Vectores de fuerza:** 
Vectores que representan una fuerza aplicada en un punto. 
Por ejemplo, el vector $\mathbf{F} = (F_x, F_y)$ representa una fuerza aplicada en el plano con componentes $F_x$ y $F_y$.
## **Vectores de velocidad:** 
Vectores que representan la velocidad de un objeto en movimiento. 
Por ejemplo, el vector $\mathbf{v} = (v_x, v_y)$ representa la velocidad de un objeto en el plano con componentes $v_x$ y $v_y$.
## **Vectores de aceleración:** 
Vectores que representan la aceleración de un objeto en movimiento. 
Por ejemplo, el vector $\mathbf{a} = (a_x, a_y)$ representa la aceleración de un objeto en el plano con componentes $a_x$ y $a_y$.
## **Vectores de momento:** 
Vectores que representan el momento de una fuerza aplicada en un punto. 
Por ejemplo, el vector $\mathbf{M} = (M_x, M_y)$ representa el momento de una fuerza en el plano con componentes $M_x$ y $M_y$.
## **Vectores de desplazamiento angular:** 
Vectores que representan el desplazamiento angular de un objeto en rotación. 
Por ejemplo, el vector $\mathbf{\theta} = (\theta_x, \theta_y)$ representa el desplazamiento angular de un objeto en el plano con componentes $\theta_x$ y $\theta_y$.
# **Propiedades de los Vectores:**
Los vectores tienen varias propiedades importantes que son fundamentales en álgebra lineal. Algunas de estas propiedades incluyen:
## **Conmutatividad:** 
La suma de dos vectores es conmutativa, es decir, $\mathbf{u} + \mathbf{v} = \mathbf{v} + \mathbf{u}$.
## **Asociatividad:** 
La suma de tres vectores es asociativa, es decir, $(\mathbf{u} + \mathbf{v}) + \mathbf{w} = \mathbf{u} + (\mathbf{v} + \mathbf{w})$.
## **Elemento neutro:** 
Existe un vector nulo $\mathbf{0}$ tal que $\mathbf{u} + \mathbf{0} = \mathbf{u}$ para cualquier vector $\mathbf{u}$.

## **Inverso aditivo:** 
Para cada vector $\mathbf{u}$, existe un vector opuesto $-\mathbf{u}$ tal que $\mathbf{u} + (-\mathbf{u}) = \mathbf{0}$.

## **Distributividad:** 
La multiplicación de un vector por un escalar es distributiva respecto a la suma de vectores, es decir, $c(\mathbf{u} + \mathbf{v}) = c\mathbf{u} + c\mathbf{v}$.

## **Compatibilidad con la multiplicación de escalares:** 
La multiplicación de un vector por un escalar es compatible con la multiplicación de escalares, es decir, $(c_1 c_2) \mathbf{u} = c_1 (c_2 \mathbf{u})$.
## **Identidad multiplicativa:** 
Existe un escalar $1$ tal que $1 \cdot \mathbf{u} = \mathbf{u}$ para cualquier vector $\mathbf{u}$.
## **Norma:** 
La norma de un vector es una medida de su magnitud y se define como $\|\mathbf{u}\| = \sqrt{\mathbf{u} \cdot \mathbf{u}}$.
## **Ángulo entre vectores:** 
El ángulo entre dos vectores se puede calcular utilizando el producto punto y las normas de los vectores, como se mencionó anteriormente.
# **Ejemplos de Vectores en Diferentes Contextos:**

## **Vectores en Física:** 
En física, los vectores se utilizan para representar cantidades como fuerza, velocidad y aceleración. Por ejemplo, la fuerza $\mathbf{F} = (3, 4)$ puede representar una fuerza de 3 unidades en la dirección $x$ y 4 unidades en la dirección $y$.
## **Vectores en Gráficos por Computadora:** 
En gráficos por computadora, los vectores se utilizan para representar posiciones de píxeles, colores y transformaciones geométricas. Por ejemplo, un vector de color $\mathbf{c} = (255, 0, 0)$ puede representar el color rojo en un sistema RGB.