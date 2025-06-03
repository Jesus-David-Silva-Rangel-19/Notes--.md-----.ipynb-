# Python: Variables y Tipos de Datos

# Variables

Las variables son contenedores que almacenan datos. En Python, no es necesario declarar el tipo de dato de una variable antes de asignarle un valor.

**Ejemplo de declaración de variables:**

```python
nombre = "Juan" # Cadena de texto (str)
edad = 30 # Entero (int)
altura = 1.75 # Decimal (float)
es_estudiante = True # Booleano (bool)
```

> **Dato:** Las variables son útiles para almacenar información que se puede utilizar y modificar a lo largo del programa.

# **Tipos de datos**

En Python, existen varios tipos de datos que se utilizan para almacenar diferentes tipos de información. A continuación, se presentan los tipos de datos más comunes junto con ejemplos:

## Números enteros (`int`)

Los números enteros son valores numéricos sin decimales. Pueden ser positivos o negativos.

**Ejemplo:**

```python
a = 10
b = -5
c = 0
print("Entero:", a, type(a))
```
> **Dato:** Los números enteros son útiles para contar, realizar cálculos matemáticos y representar cantidades discretas.

## Números decimales (`float`)
Los números decimales son valores numéricos que pueden tener una parte fraccionaria. Se utilizan para representar cantidades con precisión.

**Ejemplo:**

```python
b = 3.14
print("Decimal:", b, type(b))
```

>**Dato:** Los números decimales son útiles para cálculos que requieren precisión, como mediciones y finanzas.

## Cadenas de texto (`str`)

Las cadenas de texto son secuencias de caracteres que se utilizan para representar texto. Se definen entre comillas simples o dobles.

**Ejemplo:**
```python
c = "Hola, mundo"
d = 'Python es genial'
print("Cadena:", c, type(c))
```

> **Dato:** Las cadenas de texto son útiles para almacenar y manipular información textual, como nombres, descripciones y mensajes.

## Booleanos (`bool`)

Los booleanos son un tipo de dato que puede tener solo dos valores: `True` (verdadero) o `False` (falso). Se utilizan para representar condiciones lógicas.

**Ejemplo:**
```python
d = True
e = False
print("Booleano:", d, type(d))
```
> **Dato:** Los booleanos son útiles para tomar decisiones en el código, como en estructuras de control (`if`, `while`, etc.).

## Listas (`list`)

Las listas son colecciones ordenadas de elementos que pueden contener diferentes tipos de datos. Se definen entre corchetes `[]`.

**Ejemplo:**
```python
e = [1, 2, 3, "Hola", True]
print("Lista:", e, type(e))
```
> **Dato:** Las listas son útiles para almacenar múltiples elementos relacionados, como una colección de nombres, números o cualquier otro tipo de dato.

## Diccionarios (`dict`)

Los diccionarios son colecciones no ordenadas de pares clave-valor. Se definen entre llaves `{}` y se utilizan para almacenar información de manera estructurada.

**Ejemplo:**

```python
f = {"nombre": "Juan", "edad": 30, "ciudad": "Madrid"}
print("Diccionario:", f, type(f))
```

> **Dato:** Los diccionarios son útiles para almacenar datos relacionados, como información de una persona, donde cada clave representa un atributo y su valor asociado.

## Tuplas (`tuple`)

Las tuplas son colecciones ordenadas e inmutables de elementos. Se definen entre paréntesis `()` y se utilizan para almacenar datos que no deben cambiar.

**Ejemplo:**
```python
g = (1, 2, 3)
print("Tupla:", g, type(g))
```

> **Dato:** Las tuplas son útiles para almacenar datos que no deben modificarse, como coordenadas geográficas o fechas.

## Conjuntos (`set`)

Los conjuntos son colecciones no ordenadas de elementos únicos. Se definen entre llaves `{}` y se utilizan para realizar operaciones matemáticas como la unión, intersección y diferencia.

**Ejemplo:**
```python
h = {1, 2, 3, 4, 5}
print("Conjunto:", h, type(h))
```
> **Dato:** Los conjuntos son útiles para almacenar elementos únicos y realizar operaciones matemáticas, como eliminar duplicados de una lista.

# Tabla de tipos de datos en Python

| Tipo de dato | Nombre      | Ejemplo              |
|--------------|-------------|----------------------|
| `str`        | Texto       | `"Hola, mundo"`      |
| `int`        | Entero      | `42`                 |
| `float`      | Decimal     | `3.14`               |
| `bool`       | Booleano    | `True`, `False`      |
| `list`       | Lista       | `[1, 2, 3]`          |
| `dict`       | Diccionario | `{"clave": "valor"}` |
| `tuple`      | Tupla       | `(1, 2, 3)`          |
| `set`        | Conjunto    | `{1, 2, 3}`          |

## **Ejemplos completos de tipos de datos en Python**

``` python
# Números enteros (int)
a = 10
print("Entero:", a, type(a))

# Números decimales (float)
b = 3.14
print("Decimal:", b, type(b))

# Cadenas de texto (str)
c = "Hola, mundo"
print("Cadena:", c, type(c))

# Booleanos (bool)
d = True
print("Booleano:", d, type(d))

# Listas (list)
e = [1, 2, 3, 4, 5]
print("Lista:", e, type(e))

# Diccionarios (dict)
f = {"nombre": "Juan", "edad": 30}
print("Diccionario:", f, type(f))

# Tuplas (tuple)
g = (1, 2, 3)
print("Tupla:", g, type(g))

# Conjuntos (set)
h = {1, 2, 3, 4, 5}
print("Conjunto:", h, type(h))
```

# Resumen de tipos de datos en Python

## **¿Que representa cada tipo de dato?**

- `int`: Son números enteros, como *1, 2, 3*.

- `float`: Son números decimales, como *3.14, 2.5*.

- `str`: Son cadenas de texto, como *"Hola, mundo"*.

- `bool`: Son valores booleanos, como *True* o *False*.

- `list`: Son listas, que pueden contener múltiples elementos, como *[1, 2, 3]*.

- `dict`: Son diccionarios, que almacenan pares clave-valor, como *{"nombre": "Juan", "edad": 30}*.

- `tuple`: Son tuplas, que son similares a las listas pero inmutables, como *(1, 2, 3)*.

- `set`: Son conjuntos, que almacenan elementos únicos, como *{1, 2, 3}*.


# Ejemplos de uso de tipos de datos

## Enteros (`int`)

```python
numero_entero = 42
print("Número entero:", numero_entero, type(numero_entero))
```

> **Descripción:** Este ejemplo muestra cómo declarar una variable de tipo entero y su tipo.
> **Salida:** `42 <class 'int'>`

## Decimales (`float`)

```python
numero_decimal = 3.14
print("Número decimal:", numero_decimal, type(numero_decimal))
```
> **Descripción:** Este ejemplo muestra cómo declarar una variable de tipo decimal y su tipo.
> **Salida:** `3.14 <class 'float'>`

## Cadenas de texto (`str`)

```python
texto = "Hola, Python"
print("Texto:", texto, type(texto))
```
> **Descripción:** Este ejemplo muestra cómo declarar una variable de tipo cadena de texto y su tipo.
> **Salida:** `Hola, Python <class 'str'>`

## Booleanos (`bool`)

```python
es_mayor_de_edad = True
if es_mayor_de_edad:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")    
```

> **Descripción:** Este ejemplo muestra cómo usar una variable booleana en una estructura de control.
> **Salida:** `Eres mayor de edad.`
> **Nota:** Puedes cambiar el valor de `es_mayor_de_edad` a `False` para ver el otro resultado.

## Listas (`list`)

```python
mi_lista = [1, 2, 3, "Hola", True]
print("Lista:", mi_lista, type(mi_lista))
```
> **Descripción:** Este ejemplo muestra cómo declarar una lista que contiene diferentes tipos de datos y su tipo.

> **Salida:** `[1, 2, 3, 'Hola', True] <class 'list'>`

> **Nota:** Las listas son mutables, lo que significa que puedes modificar su contenido después de haberlas creado.

## **¿Qué son los diccionarios?**

``` python
diccionario = {
    "nombre": "Juan",
    "edad": 30,
    "ciudad": "Madrid"
}
print("Diccionario:", diccionario, type(diccionario))
```
> **Descripción:** Este ejemplo muestra cómo declarar un diccionario que almacena información relacionada y su tipo.
> **Salida:** `{'nombre': 'Juan', 'edad': 30, 'ciudad': 'Madrid'} <class 'dict'>`
> **Nota:** Los diccionarios son útiles para almacenar datos estructurados y acceder a ellos mediante claves.

## Tuplas (`tuple`)

```python
tupla = (1, 2, 3)
print("Tupla:", tupla, type(tupla))
```
> **Descripción:** Este ejemplo muestra cómo declarar una tupla, que es similar a una lista pero inmutable, y su tipo.

> **Salida:** `(1, 2, 3) <class 'tuple'>`

> **Nota:** Las tuplas son útiles para almacenar datos que no deben cambiar, como coordenadas o fechas.


## Conjuntos (`set`)

```python
conjunto = {1, 2, 3, 4, 5}
print("Conjunto:", conjunto, type(conjunto))
```
> **Descripción:** Este ejemplo muestra cómo declarar un conjunto, que almacena elementos únicos, y su tipo.

> **Salida:** `{1, 2, 3, 4, 5} <class 'set'>`

> **Nota:** Los conjuntos son útiles para realizar operaciones matemáticas como la unión, intersección y diferencia.
