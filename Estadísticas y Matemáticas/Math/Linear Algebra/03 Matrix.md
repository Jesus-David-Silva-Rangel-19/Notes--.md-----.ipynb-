# **¿Qué es una Matriz?**

Una matriz es una estructura rectangular de números, símbolos o expresiones, dispuestos en filas y columnas. Las matrices se utilizan para representar sistemas de ecuaciones lineales, transformaciones lineales y otros conceptos en álgebra lineal.

Las matrices se denotan comúnmente con letras mayúsculas, como $\mathbf{A}$, $\mathbf{B}$ o $\mathbf{C}$. Una matriz de tamaño $m \times n$ tiene $m$ filas y $n$ columnas.

## **Operaciones con Matrices:**

Las operaciones básicas con matrices incluyen:

- **Suma de matrices**: Dos matrices del mismo tamaño se pueden sumar elemento a elemento.

- **Multiplicación de matrices**: La multiplicación de matrices se realiza mediante el producto escalar de filas y columnas, y es fundamental para representar transformaciones lineales.

- **Transposición**: La transposición de una matriz $\mathbf{A}$, denotada como $\mathbf{A}^T$, intercambia sus filas y columnas.

- **Determinante**: El determinante de una matriz cuadrada es un valor escalar que proporciona información sobre la invertibilidad de la matriz y el volumen de la transformación lineal que representa.

## **Ejemplo de una Matriz:**

Una matriz $2 \times 3$ podría ser:

$$
\mathbf{A} = \begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{pmatrix}
$$

Esta matriz tiene 2 filas y 3 columnas, y cada elemento se denota por su posición en la matriz, como $a_{11} = 1$, $a_{12} = 2$, etc.

---

## **Ejemplos de operaciones con Vectores y Matrices:**

### **Suma de Vectores:**

Si tenemos dos vectores $\mathbf{u} = (1, 2)$ y $\mathbf{v} = (3, 4)$, su suma se calcula como:

$$
\mathbf{u} + \mathbf{v} = (1 + 3, 2 + 4) = (4, 6)
$$

### **Multiplicación de un Vector por un Escalar:**

Si multiplicamos el vector $\mathbf{u} = (1, 2)$ por un escalar $k = 3$, obtenemos:

$$
k \cdot \mathbf{u} = 3 \cdot (1, 2) = (3, 6)
$$

### **Multiplicación de Matrices:**

Si tenemos dos matrices $\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}$ y $\mathbf{B} = \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix}$, su producto se calcula como:

$$
\mathbf{A} \cdot \mathbf{B} = \begin{pmatrix}
1 \cdot 5 + 2 \cdot 7 & 1 \cdot 6 + 2 \cdot 8 \\
3 \cdot 5 + 4 \cdot 7 & 3 \cdot 6 + 4 \cdot 8
\end{pmatrix} = \begin{pmatrix}
19 & 22 \\
43 & 50
\end{pmatrix}
$$

# **Transposición de una Matriz:**

La transposición de una matriz $\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}$ se denota como $\mathbf{A}^T$ y se obtiene intercambiando sus filas y columnas:

$$
\mathbf{A}^T = \begin{pmatrix}
1 & 3 \\
2 & 4
\end{pmatrix}
$$

# **Determinante de una Matriz:**

El determinante de una matriz cuadrada $2 \times 2$ se calcula como:

Si tenemos la matriz $\mathbf{A} = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$, su determinante se calcula como:

$$
\text{det}(\mathbf{A}) = ad - bc
$$

Por ejemplo, para la matriz $\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}$, el determinante es:

$$
\text{det}(\mathbf{A}) = 1 \cdot 4 - 2 \cdot 3 = 4 - 6 = -2
$$

# **Suma de Matrices:**
La suma de matrices se realiza elemento a elemento. Si tenemos dos matrices $\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}$ y $\mathbf{B} = \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix}$, su suma se calcula como:

$$
\mathbf{A} + \mathbf{B} = \begin{pmatrix} 1 + 5 & 2 + 6 \\ 3 + 7 & 4 + 8 \end{pmatrix} = \begin{pmatrix} 6 & 8 \\ 10 & 12 \end{pmatrix}
$$
# **Producto de Matrices:**
El producto de matrices se realiza mediante el producto escalar de filas y columnas. Si tenemos dos matrices $\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}$ y $\mathbf{B} = \begin{pmatrix} 5 & 6 \\ 7 & 8 \end{pmatrix}$, su producto se calcula como:
$$
\mathbf{A} \cdot \mathbf{B} = \begin{pmatrix}
1 \cdot 5 + 2 \cdot 7 & 1 \cdot 6 + 2 \cdot 8 \\
3 \cdot 5 + 4 \cdot 7 & 3 \cdot 6 + 4 \cdot 8
\end{pmatrix} = \begin{pmatrix}
19 & 22 \\
43 & 50
\end{pmatrix}
$$

# **Inversa de una Matriz:**
La inversa de una matriz cuadrada $\mathbf{A}$, denotada como $\mathbf{A}^{-1}$, es la matriz que satisface la ecuación:
$$
\mathbf{A} \cdot \mathbf{A}^{-1} = \mathbf{I}
$$
donde $\mathbf{I}$ es la matriz identidad. La inversa solo existe si el determinante de la matriz es diferente de cero.
Para una matriz $2 \times 2$ $\mathbf{A} = \begin{pmatrix} a & b \\ c & d \end{pmatrix}$, la inversa se calcula como:
$$
\mathbf{A}^{-1} = \frac{1}{\text{det}(\mathbf{A})} \begin{pmatrix} d & -b \\ -c & a \end{pmatrix}
$$


Por ejemplo, para la matriz $\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}$, su inversa es:
$$
\mathbf{A}^{-1} = \frac{1}{-2} \begin{pmatrix} 4 & -2 \\ -3 & 1 \end{pmatrix} = \begin{pmatrix} -2 & 1 \\ \frac{3}{2} & -\frac{1}{2} \end{pmatrix}
$$
# **Propiedades de las Matrices:**
Las matrices tienen varias propiedades importantes, como la asociatividad, conmutatividad y distributividad. Algunas de estas propiedades son:
## **Asociatividad**: 
$(\mathbf{A} + \mathbf{B}) + \mathbf{C} = \mathbf{A} + (\mathbf{B} + \mathbf{C})$ y $(\mathbf{A} \cdot \mathbf{B}) \cdot \mathbf{C} = \mathbf{A} \cdot (\mathbf{B} \cdot \mathbf{C})$.
## **Conmutatividad**: 
$\mathbf{A} + \mathbf{B} = \mathbf{B} + \mathbf{A}$ (suma) y $\mathbf{A} \cdot \mathbf{B} \neq \mathbf{B} \cdot \mathbf{A}$ (multiplicación en general).
## **Distributividad**: 
$\mathbf{A} \cdot (\mathbf{B} + \mathbf{C}) = \mathbf{A} \cdot \mathbf{B} + \mathbf{A} \cdot \mathbf{C}$.
## **Identidad**: 
$\mathbf{A} \cdot \mathbf{I} = \mathbf{A}$ y $\mathbf{I} \cdot \mathbf{A} = \mathbf{A}$, donde $\mathbf{I}$ es la matriz identidad.
## **Inversa**: 
$\mathbf{A} \cdot \mathbf{A}^{-1} = \mathbf{I}$ y $\mathbf{A}^{-1} \cdot \mathbf{A} = \mathbf{I}$, donde $\mathbf{A}^{-1}$ es la inversa de la matriz $\mathbf{A}$.
## **Transposición**: 
$(\mathbf{A} + \mathbf{B})^T = \mathbf{A}^T + \mathbf{B}^T$ y $(\mathbf{A} \cdot \mathbf{B})^T = \mathbf{B}^T \cdot \mathbf{A}^T$.
## **Determinante**: 
$\text{det}(\mathbf{A} \cdot \mathbf{B}) = \text{det}(\mathbf{A}) \cdot \text{det}(\mathbf{B})$ y $\text{det}(\mathbf{A}^T) = \text{det}(\mathbf{A})$.
## **Rango**: 
El rango de una matriz es el número máximo de vectores linealmente independientes en la matriz. Se denota como $\text{rank}(\mathbf{A})$.
## **Nulidad**: 
La nulidad de una matriz es el número de soluciones linealmente independientes para la ecuación homogénea $\mathbf{A} \mathbf{x} = \mathbf{0}$. Se denota como $\text{nullity}(\mathbf{A})$.
## **Espacio columna**: 
El espacio columna de una matriz es el espacio vectorial generado por las columnas de la matriz. Se denota como $\text{im}(\mathbf{A})$.
## **Espacio nulo**: 
El espacio nulo de una matriz es el espacio vectorial de todas las soluciones a la ecuación homogénea $\mathbf{A} \mathbf{x} = \mathbf{0}$. Se denota como $\text{ker}(\mathbf{A})$.
## **Espacio generado**: 
El espacio generado por un conjunto de vectores es el conjunto de todas las combinaciones lineales posibles de esos vectores. Se denota como $\text{span}(\mathbf{v}_1, \mathbf{v}_2, \ldots, \mathbf{v}_k)$.
## **Dimensión**: 
La dimensión de un espacio vectorial es el número máximo de vectores linealmente independientes en ese espacio. 
Se denota como $\text{dim}(\mathbf{V})$.
## **Producto escalar**: 
El producto escalar entre dos vectores $\mathbf{u}$ y $\mathbf{v}$ se denota como $\mathbf{u} \cdot \mathbf{v}$ y se calcula como la suma de los productos de sus componentes correspondientes.
## **Producto cruz**: 
El producto cruz entre dos vectores $\mathbf{u}$ y $\mathbf{v}$ se denota como $\mathbf{u} \times \mathbf{v}$ y se calcula como un vector perpendicular a ambos vectores (solo en $\mathbb{R}^3$).
## **Norma**: 
La norma de un vector $\mathbf{v}$ se denota como $\|\mathbf{v}\|$ y se calcula como la raíz cuadrada de la suma de los cuadrados de sus componentes.
## **Ángulo**: 
El ángulo entre dos vectores $\mathbf{u}$ y $\mathbf{v}$ se denota como $\angle(\mathbf{u}, \mathbf{v})$ y se calcula utilizando el producto escalar y la norma de los vectores.
## **Suma directa**: 
La suma directa de dos vectores $\mathbf{u}$ y $\mathbf{v}$ se denota como $\mathbf{u} \oplus \mathbf{v}$ y se calcula como la concatenación de los vectores.
## **Producto tensorial**: 
El producto tensorial entre dos vectores $\mathbf{u}$ y $\mathbf{v}$ se denota como $\mathbf{u} \otimes \mathbf{v}$ y se calcula como una matriz cuyas entradas son los productos de las componentes de los vectores.
## **Producto Hadamard**: 
El producto Hadamard entre dos matrices $\mathbf{A}$ y $\mathbf{B}$ se denota como $\mathbf{A} \circ \mathbf{B}$ y se calcula como el producto elemento a elemento de las matrices.
## **Suma de matrices**: 
La suma de matrices se denota como $\mathbf{A} \oplus \mathbf{B}$ y se calcula como la suma elemento a elemento de las matrices.
## **Producto tensorial de matrices**: 
El producto tensorial entre dos matrices $\mathbf{A}$ y $\mathbf{B}$ se denota como $\mathbf{A} \otimes \mathbf{B}$ y se calcula como una matriz cuyas entradas son los productos de las entradas de las matrices.
## **Matrices equivalentes**: 
Dos matrices $\mathbf{A}$ y $\mathbf{B}$ son equivalentes si tienen el mismo rango, lo que se denota como $\mathbf{A} \sim \mathbf{B}$.
## **Matrices similares**: 
Dos matrices $\mathbf{A}$ y $\mathbf{B}$ son similares si existe una matriz invertible $\mathbf{P}$ tal que $\mathbf{A} = \mathbf{P} \cdot \mathbf{B} \cdot \mathbf{P}^{-1}$.
## **Matrices ortogonales**: 
Una matriz $\mathbf{A}$ es ortogonal si su transpuesta es igual a su inversa, es decir, $\mathbf{A}^T = \mathbf{A}^{-1}$.
## **Matrices simétricas**: 
Una matriz $\mathbf{A}$ es simétrica si $\mathbf{A}^T = \mathbf{A}$.
## **Matrices antisimétricas**: 
Una matriz $\mathbf{A}$ es antisimétrica si $\mathbf{A}^T = -\mathbf{A}$.
## **Matrices diagonales**: 
Una matriz es diagonal si todos sus elementos fuera de la diagonal principal son cero.
## **Matrices escalar**: 
Una matriz es escalar si todos sus elementos de la diagonal principal son iguales.
## **Matrices unitarias**: 
Una matriz $\mathbf{U}$ es unitaria si $\mathbf{U}^* \cdot \mathbf{U} = \mathbf{I}$, donde $\mathbf{U}^*$ es la conjugada transpuesta de $\mathbf{U}$.
## **Matrices hermitianas**: 
Una matriz $\mathbf{A}$ es hermitiana si $\mathbf{A}^* = \mathbf{A}$, donde $\mathbf{A}^*$ es la conjugada transpuesta de $\mathbf{A}$.

# **Tipos de Matrices:**
## **Matriz Cuadrada**: 
Una matriz con el mismo número de filas y columnas.

Ejemplo: $\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}$ es una matriz cuadrada de tamaño $2 \times 2$.
## **Matriz Rectangular**: 
Una matriz con un número diferente de filas y columnas.

Ejemplo: 

$\mathbf{B} = \begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix}$ es una matriz rectangular de tamaño $2 \times 3$.
## **Matriz Nula**: 
Una matriz en la que todos sus elementos son cero.

Ejemplo: 

$\mathbf{C} = \begin{pmatrix} 0 & 0 & 0 \\ 0 & 0 & 0 \end{pmatrix}$ es una matriz nula de tamaño $2 \times 3$.
## **Matriz Identidad**: 
Una matriz cuadrada en la que todos los elementos de la diagonal principal son uno y los demás son cero.

Ejemplo: 

$\mathbf{I} = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}$ es una matriz identidad de tamaño $2 \times 2$.
## **Matriz Diagonal**: 
Una matriz cuadrada en la que todos los elementos fuera de la diagonal principal son cero.

Ejemplo: 

$\mathbf{D} = \begin{pmatrix} 1 & 0 \\ 0 & 2 \end{pmatrix}$ es una matriz diagonal de tamaño $2 \times 2$.
## **Matriz Escalar**: 
Una matriz diagonal en la que todos los elementos de la diagonal principal son iguales.

Ejemplo: 

$\mathbf{S} = \begin{pmatrix} 3 & 0 \\ 0 & 3 \end{pmatrix}$ es una matriz escalar de tamaño $2 \times 2$.
## **Matriz Simétrica**: 
Una matriz cuadrada que es igual a su transpuesta.

Ejemplo: 

$\mathbf{A} = \begin{pmatrix} 1 & 2 \\ 2 & 3 \end{pmatrix}$ es una matriz simétrica de tamaño $2 \times 2$.
## **Matriz Antisimétrica**: 
Una matriz cuadrada que es igual a su transpuesta multiplicada por -1.


Ejemplo: 

$\mathbf{A} = \begin{pmatrix} 0 & 2 \\ -2 & 0 \end{pmatrix}$ es una matriz antisimétrica de tamaño $2 \times 2$.
## **Matriz Ortogonal**: 
Una matriz cuadrada cuyas columnas y filas son vectores ortonormales.

Ejemplo: 

$\mathbf{Q} = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}$ es una matriz ortogonal de tamaño $2 \times 2$.
## **Matriz Unitaria**: 
Una matriz cuadrada cuyas columnas y filas son vectores ortonormales complejos.

Ejemplo: 

$\mathbf{U} = \begin{pmatrix} 1 & 0 \\ 0 & i \end{pmatrix}$ es una matriz unitaria de tamaño $2 \times 2$.
## **Matriz Hermitiana**: 
Una matriz cuadrada que es igual
a su conjugada transpuesta.

Ejemplo: 

$\mathbf{H} = \begin{pmatrix} 1 & 2+i \\ 2-i & 3 \end{pmatrix}$ es una matriz hermitiana de tamaño $2 \times 2$.
## **Matriz Triangular Superior**: 
Una matriz cuadrada en la que todos los elementos por debajo de la diagonal principal son cero.

Ejemplo: 

$\mathbf{T} = \begin{pmatrix} 1 & 2 \\ 0 & 3 \end{pmatrix}$ es una matriz triangular superior de tamaño $2 \times 2$.
## **Matriz Triangular Inferior**: 
Una matriz cuadrada en la que todos los elementos por encima de la diagonal principal son cero.


Ejemplo: 

$\mathbf{L} = \begin{pmatrix} 1 & 0 \\ 2 & 3 \end{pmatrix}$ es una matriz triangular inferior de tamaño $2 \times 2$.
## **Matriz de Vandermonde**: 
Una matriz en la que cada fila es una progresión geométrica.

Ejemplo: 

$\mathbf{V} = \begin{pmatrix} 1 & 1 & 1 \\ 1 & 2 & 4 \\ 1 & 3 & 9 \end{pmatrix}$ es una matriz de Vandermonde de tamaño $3 \times 3$.
## **Matriz de Toeplitz**:
Una matriz en la que cada elemento es igual al elemento en la diagonal principal más un desplazamiento constante.

Ejemplo: 

$\mathbf{T} = \begin{pmatrix} 1 & 2 & 3 \\ 4 & 1 & 2 \\ 5 & 4 & 1 \end{pmatrix}$ es una matriz de Toeplitz de tamaño $3 \times 3$.
## **Matriz de Hilbert**:
Una matriz cuadrada en la que cada elemento es el inverso de la suma de sus índices más uno.

Ejemplo:

$\mathbf{H} = \begin{pmatrix} 1 & \frac{1}{2} & \frac{1}{3} \\ \frac{1}{2} & \frac{1}{3} & \frac{1}{4} \\ \frac{1}{3} & \frac{1}{4} & \frac{1}{5} \end{pmatrix}$ es una matriz de Hilbert de tamaño $3 \times 3$.

# **Las 5 matrices más importantes en álgebra lineal:**

## **1. Matriz Identidad**: 

Representa la transformación lineal que no cambia los vectores.

Ejemplo: 

$\mathbf{I} = \begin{pmatrix} 1 & 0 \\ 0 & 1 \end{pmatrix}$.

## **2. Matriz Cero**:
Representa la transformación lineal que lleva todos los vectores al vector nulo.

Ejemplo:

$\mathbf{0} = \begin{pmatrix} 0 & 0 \\ 0 & 0 \end{pmatrix}$.

## **3. Matriz Diagonal**:
Representa una transformación lineal que escala los vectores en diferentes direcciones.

Ejemplo:

$\mathbf{D} = \begin{pmatrix} 2 & 0 \\ 0 & 3 \end{pmatrix}$.

## **4. Matriz de Proyección**:
Representa la transformación lineal que proyecta los vectores sobre un subespacio.

Ejemplo:

$\mathbf{P} = \begin{pmatrix} 1 & 0 \\ 0 & 0 \end{pmatrix}$ (proyección sobre el eje $x$).

## **5. Matriz de Rotación**:

Representa la transformación lineal que rota los vectores en el plano.

Ejemplo:

$\mathbf{R} = \begin{pmatrix} \cos(\theta) & -\sin(\theta) \\ \sin(\theta) & \cos(\theta) \end{pmatrix}$, donde $\theta$ es el ángulo de rotación.

# **Las 5 matrices más usadas de Data Science y Machine Learning:**

## **1. Matriz de Confusión**:
Una matriz que muestra el rendimiento de un modelo de clasificación, comparando las predicciones con las etiquetas reales.

Ejemplo:

$\begin{pmatrix} TP & FN \\ FP & TN \end{pmatrix}$

donde $TP$ es verdadero positivo, $FN$ es falso negativo, $FP$ es falso positivo y $TN$ es verdadero negativo.

## **2. Matriz de Covarianza**:

Una matriz que muestra la covarianza entre diferentes variables en un conjunto de datos.

Ejemplo:

$\mathbf{C} = \begin{pmatrix} \sigma^2_1 & \sigma_{12} \\ \sigma_{21} & \sigma^2_2 \end{pmatrix}$

donde $\sigma^2_1$ y $\sigma^2_2$ son las varianzas de las variables 1 y 2, y $\sigma_{12}$ es la covarianza entre ellas.

## **3. Matriz de Correlación**:
Una matriz que muestra la correlación entre diferentes variables en un conjunto de datos.

Ejemplo:

$\mathbf{R} = \begin{pmatrix} 1 & r_{12} \\ r_{21} & 1 \end{pmatrix}$

donde $r_{12}$ es la correlación entre las variables 1 y 2.

## **4. Matriz de Características**:

Una matriz que representa las características de un conjunto de datos, donde cada fila es una observación y cada columna es una característica.

Ejemplo:

$\mathbf{X} = \begin{pmatrix} x_{11} & x_{12} & \cdots & x_{1n} \\ x_{21} & x_{22} & \cdots & x_{2n} \\ \vdots & \vdots & \ddots & \vdots \\ x_{m1} & x_{m2} & \cdots & x_{mn} \end{pmatrix}$

donde cada $x_{ij}$ es una característica de la observación $i$.


## **5. Matriz de Ponderación**:
Una matriz que contiene los pesos asignados a diferentes características en un modelo de aprendizaje automático.

Ejemplo:
$\mathbf{W} = \begin{pmatrix} w_1 & w_2 & \cdots & w_n \end{pmatrix}$

donde cada $w_i$ es el peso asignado a la característica $i$.

# **Valores propios y vectores propios**

Los valores propios y los vectores propios son conceptos fundamentales en álgebra lineal que se utilizan para analizar las propiedades de las matrices y sus transformaciones lineales.

## **Valores Propios**:

Un valor propio de una matriz $\mathbf{A}$ es un escalar $\lambda$ tal que existe un vector no nulo $\mathbf{v}$ (llamado vector propio) que satisface la ecuación:

$$
\mathbf{A} \mathbf{v} = \lambda \mathbf{v}
$$

Esto significa que al aplicar la transformación lineal representada por la matriz $\mathbf{A}$ al vector $\mathbf{v}$, el resultado es un múltiplo escalar del mismo vector.

Los valores propios se pueden encontrar resolviendo el polinomio característico de la matriz, que se obtiene de la siguiente manera:

1. Calcular el determinante de la matriz $\mathbf{A} - \lambda \mathbf{I}$, donde $\mathbf{I}$ es la matriz identidad.

2. Igualar el determinante a cero para obtener el polinomio característico:

$$
\text{det}(\mathbf{A} - \lambda \mathbf{I}) = 0
$$

3. Resolver el polinomio para encontrar los valores propios $\lambda$.

## **Vectores Propios**:

Un vector propio de una matriz $\mathbf{A}$ es un vector no nulo $\mathbf{v}$ que satisface la ecuación:

$$
\mathbf{A} \mathbf{v} = \lambda \mathbf{v}
$$

donde $\lambda$ es un valor propio asociado a la matriz $\mathbf{A}$.

Los vectores propios se pueden encontrar sustituyendo cada valor propio $\lambda$ en la ecuación:

$$
(\mathbf{A} - \lambda \mathbf{I}) \mathbf{v} = \mathbf{0}
$$

donde $\mathbf{0}$ es el vector nulo. Esto nos da un sistema de ecuaciones lineales que se puede resolver para encontrar los vectores propios correspondientes a cada valor propio.

## **Ejemplo**:

Consideremos la matriz $\mathbf{A} = \begin{pmatrix} 4 & 1 \\ 2 & 3 \end{pmatrix}$.

1. **Encontrar los valores propios**:

Calculamos el polinomio característico:

$$
\text{det}(\mathbf{A} - \lambda \mathbf{I}) = \text{det}\left(\begin{pmatrix} 4 - \lambda & 1 \\ 2 & 3 - \lambda \end{pmatrix}\right) = (4 - \lambda)(3 - \lambda) - 2 = \lambda^2 - 7\lambda + 10 = 0
$$

Resolviendo el polinomio, encontramos los valores propios:

$$
\lambda_1 = 5, \quad \lambda_2 = 2
$$

2. **Encontrar los vectores propios**:

Para $\lambda_1 = 5$:

Sustituimos en la ecuación:

$$
(\mathbf{A} - 5 \mathbf{I}) \mathbf{v} = \begin{pmatrix} -1 & 1 \\ 2 & -2 \end{pmatrix} \begin{pmatrix} v_1 \\ v_2 \end{pmatrix} = \begin{pmatrix} 0 \\ 0 \end{pmatrix}
$$

Resolviendo el sistema, encontramos que un vector propio asociado a $\lambda_1 = 5$ es:

$$
\mathbf{v_1} = \begin{pmatrix} 1 \\ 1 \end{pmatrix}
$$

Para $\lambda_2 = 2$: