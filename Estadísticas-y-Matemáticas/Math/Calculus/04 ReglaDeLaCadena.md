# Calculo básico

# Regla de la cadena (para la retropropagación)

La regla de la cadena es una herramienta fundamental en cálculo que permite calcular la derivada de una función compuesta. En el contexto de la retropropagación en redes neuronales, se utiliza para calcular las derivadas de las funciones de activación y los pesos de la red.

## Definición de la regla de la cadena

La regla de la cadena establece que si tenemos dos funciones compuestas $f(g(x))$, la derivada de esta composición se puede calcular como:

$$\frac{d}{dx}f(g(x)) = f'(g(x)) \cdot g'(x)$$

Esto significa que para encontrar la derivada de una función compuesta, primero se calcula la derivada de la función exterior $f$ con respecto a su argumento $g(x)$, y luego se multiplica por la derivada de la función interior $g(x)$ con respecto a $x$.

## Aplicación en retropropagación

En el contexto de la retropropagación, la regla de la cadena se utiliza para calcular las derivadas parciales de la función de pérdida con respecto a los pesos y sesgos de la red neuronal. Esto es esencial para actualizar los parámetros de la red durante el proceso de entrenamiento.

Para aplicar la regla de la cadena en retropropagación, se sigue el siguiente procedimiento:

1. **Calcular la salida de la red**: Se realiza una pasada hacia adelante a través de la red para obtener la salida final.
   
2. **Calcular el error**: Se calcula el error entre la salida esperada y la salida real de la red.
   
3. **Retropropagar el error**: Se utiliza la regla de la cadena para calcular las derivadas parciales del error con respecto a cada peso y sesgo de la red, comenzando desde la capa de salida y retrocediendo hacia las capas anteriores.
   
4. **Actualizar los pesos y sesgos**: Se utilizan las derivadas calculadas para actualizar los pesos y sesgos de la red utilizando un algoritmo de optimización, como el descenso de gradiente.
   
5. **Repetir el proceso**: Se repite el proceso para cada lote de datos durante el entrenamiento.
   
6. **Ajustar la tasa de aprendizaje**: Se puede ajustar la tasa de aprendizaje para controlar la magnitud de los cambios en los pesos y sesgos durante el entrenamiento.
   
7. **Monitorear el rendimiento**: Se monitorea el rendimiento de la red en un conjunto de validación para evitar el sobreajuste y ajustar los hiperparámetros según sea necesario.

8.  **Finalizar el entrenamiento**: Una vez que la red alcanza un rendimiento satisfactorio, se finaliza el entrenamiento y se guarda el modelo para su uso posterior.

## Ejemplo de aplicación

Supongamos que tenemos una red neuronal con una función de activación $f(x) = \sigma(x)$, donde $\sigma$ es la función sigmoide. La salida de la red es $y = f(g(x))$, donde $g(x)$ es la combinación lineal de las entradas y los pesos.

Para calcular la derivada de la salida con respecto a los pesos, aplicamos la regla de la cadena:
$$\frac{dy}{dw} = \frac{dy}{dg} \cdot \frac{dg}{dw}$$

Donde $w$ es un peso de la red. Aquí, $\frac{dy}{dg}$ es la derivada de la función sigmoide con respecto a su argumento, y $\frac{dg}{dw}$ es la derivada de la combinación lineal con respecto al peso.