# **Estadística Descriptiva**

## **Qué es la Estadística Descriptiva?**

La estadística descriptiva es una rama de la estadística que se encarga de resumir y describir las características principales de un conjunto de datos. 

A diferencia de la estadística inferencial, que busca hacer generalizaciones o predicciones sobre una población a partir de una muestra, la estadística descriptiva se centra en proporcionar una visión clara y concisa de los datos disponibles.

## **Medidas de Tendencia Central**

Las medidas de tendencia central son valores que representan un conjunto de datos y nos indican dónde se encuentra el "centro" de los datos. Las más comunes son:

- **Media**: Es el promedio de todos los valores. Se calcula sumando todos los valores y dividiendo por el número total de valores.
  
  $$
  \text{Media} = \frac{\sum_{i=1}^{n} x_i}{n}
  $$

- **Mediana**: Es el valor que divide el conjunto de datos en dos partes iguales. Si los datos están ordenados, la mediana es el valor del medio. Si hay un número par de observaciones, se toma el promedio de los dos valores centrales.|

    - Si n es impar:

    $$
    \text{Mediana} = x_{\left(\frac{n+1}{2}\right)}
    $$

    - Si n es par:
    
    $$
    \text{Mediana} = \frac{x_{\left(\frac{n}{2}\right)} + x_{\left(\frac{n}{2} + 1\right)}}{2}
    $$

- **Moda**: Es el valor que aparece con mayor frecuencia en el conjunto de datos. Un conjunto de datos puede tener una moda, más de una moda (bimodal o multimodal) o ninguna moda.

    - Ejemplo: En el conjunto de datos $(1, 2, 2, 3, 4)$, la moda es $2$ porque es el número que más veces se repite.

## **Medidas de Dispersión**

Las medidas de dispersión indican cuán dispersos o concentrados están los datos alrededor de la media. Las más comunes son:

- **Rango**: Es la diferencia entre el valor máximo y el valor mínimo del conjunto de datos.

  $$
  \text{Rango} = x_{\text{max}} - x_{\text{min}}
  $$

- **Varianza**: Mide la variabilidad de los datos respecto a la media. Se calcula como el promedio de las diferencias al cuadrado entre cada valor y la media.

    - Para una población:

    $$
    \text{Varianza} = \sigma^2 = \frac{\sum_{i=1}^{N} (x_i - \mu)^2}{N}
    $$

    - Para una muestra:

    $$
    \text{Varianza} = s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}
    $$

- **Desviación estándar**: Es la raíz cuadrada de la varianza y proporciona una medida de la dispersión en las mismas unidades que los datos originales.

    $$
    \text{Desviación estándar} = \sigma = \sqrt{\text{Varianza}}
    $$

- **Coeficiente de variación**: Es una medida relativa de la dispersión que se expresa como un porcentaje. Se calcula dividiendo la desviación estándar entre la media y multiplicando por 100.

    $$
    \text{Coeficiente de variación} = \frac{\sigma}{\mu} \times 100
    $$

## **Medidas de Posición**

Las medidas de posición indican la ubicación relativa de un valor dentro de un conjunto de datos. Algunas de las más comunes son:

- **Cuartiles**: Dividen el conjunto de datos en cuatro partes iguales. El primer cuartil (Q1) es el valor que separa el 25% inferior de los datos, el segundo cuartil (Q2) es la mediana y el tercer cuartil (Q3) separa el 75% inferior del 25% superior.

    - Cálculo de cuartiles:
    
    $$
    Q_k = x_{\left(\frac{kn}{4}\right)}
    $$

- **Deciles**: Dividen el conjunto de datos en diez partes iguales. El primer decil (D1) es el valor que separa el 10% inferior de los datos, el segundo decil (D2) separa el 20% inferior, y así sucesivamente.

    - Cálculo de deciles:
    
    $$
    D_k = x_{\left(\frac{kn}{10}\right)}
    $$

- **Percentiles**: Dividen el conjunto de datos en cien partes iguales. El percentil Pk es el valor que separa el k% inferior de los datos.

    - Cálculo de percentiles:
    
    $$
    P_k = x_{\left(\frac{kn}{100}\right)}
    $$

## **Distribuciones de Frecuencia**

Las distribuciones de frecuencia son tablas o gráficos que muestran la frecuencia de ocurrencia de cada valor o rango de valores en un conjunto de datos. 

Son útiles para visualizar la distribución de los datos y detectar patrones.

### **Tablas de Frecuencia**

Una tabla de frecuencia muestra cuántas veces aparece cada valor en un conjunto de datos. Puede ser simple (con valores únicos) o agrupada (con intervalos).

- **Tabla de frecuencia simple**: Muestra cada valor único y su frecuencia.

  | Valor | Frecuencia |
  |-------|------------|
  | 1     | 2          |
  | 2     | 3          |
  | 3     | 1          |
  | 4     | 4          |

- **Tabla de frecuencia acumulada**: Muestra la frecuencia acumulada hasta cada valor. Es útil para ver cuántos valores están por debajo de un cierto punto.

    | Valor | Frecuencia | Frecuencia Acumulada |
    |-------|------------|----------------------|
    | 1     | 2          | 2                    |
    | 2     | 3          | 5                    |
    | 3     | 1          | 6                    |
    | 4     | 4          | 10                   |

- **Tabla de frecuencia relativa**: Muestra la proporción de cada valor respecto al total. Se calcula dividiendo la frecuencia de cada valor por el total de observaciones.

    | Valor | Frecuencia | Frecuencia Relativa |
    |-------|------------|---------------------|
    | 1     | 2          | 0.2                 |
    | 2     | 3          | 0.3                 |
    | 3     | 1          | 0.1                 |
    | 4     | 4          | 0.4                 |

- **Tabla de frecuencia acumulada relativa**: Muestra la proporción acumulada de cada valor. Se calcula sumando las frecuencias relativas.

    | Valor | Frecuencia Relativa | Frecuencia Acumulada Relativa |
    |-------|---------------------|-------------------------------|
    | 1     | 0.2                 | 0.2                           |
    | 2     | 0.3                 | 0.5                           |
    | 3     | 0.1                 | 0.6                           |
    | 4     | 0.4                 | 1.0                           |

- **Tabla de frecuencia agrupada**: Agrupa los datos en intervalos y muestra la frecuencia de cada intervalo.

    | Intervalo | Frecuencia |
    |-----------|------------|
    | 1-2       | 5          |
    | 3-4       | 5          |

### **Gráficos de Frecuencia**

Los gráficos de frecuencia son representaciones visuales de las distribuciones de frecuencia. Los más comunes son:

- **Histograma**: Muestra la frecuencia de los datos agrupados en intervalos. Los intervalos se representan como barras, donde la altura de cada barra indica la frecuencia del intervalo.

- **Polígono de Frecuencia**: Es una línea que conecta los puntos medios de las barras del histograma. Es útil para visualizar la forma de la distribución.

- **Gráfico de Barras**: Muestra la frecuencia de valores únicos o categorías. Cada barra representa un valor o categoría, y su altura indica la frecuencia.

- **Gráfico de Pastel**: Representa la proporción de cada categoría respecto al total. Cada "rebanada" del pastel representa una categoría y su tamaño es proporcional a su frecuencia.

- **Boxplot (Diagrama de Caja)**: Muestra la mediana, los cuartiles y los valores atípicos de un conjunto de datos. Es útil para visualizar la dispersión y detectar valores extremos.