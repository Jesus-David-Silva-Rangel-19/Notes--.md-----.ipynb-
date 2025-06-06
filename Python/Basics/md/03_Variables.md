# Python: Variables y Tipos de Datos

## 1. ¿Qué son las variables?

Una **variable** es un nombre simbólico que se utiliza para almacenar datos en la memoria del computador. Cada variable tiene un nombre y un valor asociado. En Python, no es necesario declarar el tipo de variable previamente; el intérprete lo infiere automáticamente según el valor asignado.

---

## 2. ¿Qué son los tipos de datos?

Los **tipos de datos** son categorías que definen la naturaleza de los valores que puede almacenar una variable. Python posee múltiples tipos de datos incorporados, como números enteros (`int`), números decimales (`float`), cadenas de texto (`str`), listas (`list`), diccionarios (`dict`), tuplas (`tuple`), conjuntos (`set`), entre otros.

---

## 3. Ejemplos básicos de variables en Python

```python
# Texto (str)
nombre = "Juan"

# Número Entero (int)
edad = 30

# Número Decimal (float)
altura = 1.75

# Booleano (bool)
es_estudiante = True

# Lista (list)
ciudades = ["Madrid", "Barcelona", "Valencia"]

# Diccionario (dict)
paises = {
    "Francia": "París",
    "Reino Unido": "Londres",
    "EE.UU.": "Washington D.C.",
    "Colombia": "Bogotá D.C.",
    "Alemania": "Berlín"
}

# Tupla (tuple)
coordenadas = (40.4168, -3.7038)

# Conjunto (set)
conjunto = {1, 2, 3, 4, 5}
```

---

## 4. Tipos de Variables en Python

### 4.1. Cadena de texto (`str`)

Se utiliza para almacenar secuencias de caracteres.

```python
texto = "Hola, mundo!"
```

### 4.2. Número decimal (`float`)

Se utiliza para almacenar valores numéricos con parte decimal.

```python
numero_decimal = 3.14
```

### 4.3. Número entero (`int`)

Se utiliza para representar números enteros sin decimales.

```python
numero_entero = 42
```

### 4.4. Booleano (`bool`)

Representa valores de verdad: `True` o `False`.

```python
es_verdadero = True
```

### 4.5. Lista (`list`)

Contenedor ordenado y mutable de elementos.

```python
lista = [1, 2, 3, 4, 5]
```

### 4.6. Diccionario (`dict`)

Almacena pares clave-valor.

```python
diccionario = {
    "nombre": "Juan",
    "edad": 30,
    "ciudad": "Madrid"
}
```

### 4.7. Tupla (`tuple`)

Colección ordenada e inmutable de elementos.

```python
tupla = (1, 2, 3)
```

### 4.8. Conjunto (`set`)

Colección no ordenada de elementos únicos.

```python
conjunto = {1, 2, 3, 4, 5}
```

### 4.9. Ninguno (`None`)

Representa la ausencia de valor.

```python
ninguno = None
```

### 4.10. Bytes (`bytes`)

Almacena datos binarios inmutables.

```python
bytes_datos = b"Hola, mundo!"
```

### 4.11. Bytearray (`bytearray`)

Almacena datos binarios mutables.

```python
bytearray_datos = bytearray(b"Hola, mundo!")
```

### 4.12. Memoryview (`memoryview`)

Permite el acceso eficiente a datos binarios sin copiarlos.

```python
memoryview_datos = memoryview(b"Hola, mundo!")
```

### 4.13. Conjunto congelado (`frozenset`)

Colección inmutable de elementos únicos.

```python
frozenset_datos = frozenset([1, 2, 3, 4, 5])
```

### 4.14. Número complejo (`complex`)

Representa números con parte real e imaginaria.

```python
numero_complejo = 3 + 4j
```

---

> **Nota final:** Python es un lenguaje de tipado dinámico, lo que significa que el tipo de una variable puede cambiar durante la ejecución del programa si se le asigna un valor de tipo diferente. Sin embargo, se recomienda mantener la coherencia del tipo de dato para evitar errores de interpretación o lógica.

---
