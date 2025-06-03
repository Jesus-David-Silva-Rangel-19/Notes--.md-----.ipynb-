
# 🔁 **Loops o Estructuras de Iteración en Python**

## 📌 **¿Qué son?**

Las **estructuras de iteración** (también conocidas como *bucles* o *loops*) permiten **repetir un bloque de código múltiples veces** mientras se cumple una condición o al recorrer una secuencia de elementos. Son fundamentales para automatizar tareas repetitivas y procesar grandes volúmenes de datos.

En Python, existen dos estructuras principales de iteración:

- `for`
- `while`


## 🎯 **¿Para qué se usan?**

- Repetir instrucciones de forma controlada.
- Recorrer listas, cadenas, tuplas, diccionarios, archivos, etc.
- Automatizar procesos cíclicos.
- Aplicar cálculos o transformaciones a conjuntos de datos.


## 🧠 **¿Para qué son útiles?**

Estas estructuras son clave para:

- Optimizar el tiempo de ejecución al evitar repeticiones manuales.
- Realizar operaciones sobre **colecciones de datos**.
- Construir **algoritmos iterativos** como búsquedas, sumatorias,
  filtrado o generación de estructuras.
- Permitir una **programación más declarativa y limpia**.


## 📅 **¿Cuándo usar cada tipo?**

- `for`: Cuando se conoce de antemano el número de iteraciones o se
  desea recorrer una secuencia.
- `while`: Cuando se desea repetir un bloque **hasta que se cumpla una
  condición**, sin saber cuántas veces será necesario.


## 🧱 **Estructura en Python**

### 🔹 **Bucle `for`**

``` python
for variable in iterable:
    # bloque de código a repetir
```

Se utiliza para recorrer cualquier objeto iterable como listas, rangos,
cadenas, diccionarios, etc.

### 🔹 **Bucle `while`**

``` python
while condición:
    # bloque de código a repetir mientras la condición sea True
```

Repite el bloque mientras la condición lógica evaluada sea verdadera.


## 🧪 **Ejemplos prácticos**

### **Ejemplo 1: `for` con `range()`**

``` python
for i in range(5):
    print("Iteración", i)
```

### **Ejemplo 2: Recorrer una lista**

``` python
frutas = ["manzana", "banana", "pera"]
for fruta in frutas:
    print("Fruta:", fruta)
```

### **Ejemplo 3: `while` con condición**

``` python
contador = 1
while contador <= 5:
    print("Contador:", contador)
    contador += 1
```

### Ejemplo 4: Uso de `break` y `continue`

``` python
for i in range(10):
    if i == 5:
        break  # Sale del bucle cuando i es 5
    if i % 2 == 0:
        continue  # Salta a la siguiente iteración si es par
    print("Número impar:", i)
```


## 💡 **Recomendaciones**

- Evitar bucles infinitos con `while` sin condiciones de salida claras.
- Usar `enumerate()` cuando se necesiten índices en un `for`.
- Preferir `for` sobre `while` cuando se recorre una secuencia.
- Incluir `break` y `continue` con criterio, solo cuando sea necesario
  modificar el flujo.


## 📚 **Referencias**

- [Tutorial de bucles en Python – Python
  Docs](https://docs.python.org/3/tutorial/controlflow.html#for-statements)
- [Funciones útiles para iterar – `range()`,
  `enumerate()`](https://docs.python.org/3/library/functions.html#func-range)

------------------------------------------------------------------------