# 1. Python: Variables

``` python
# Texto (str)
nombre = "Juan"

# Número Entero (int)
edad = 30

# Número Decimal (float)
altura = 1.75

# Booleano (bool)
es_estudiante = True

# Listas (list)
ciudades = ["Madrid", "Barcelona", "Valencia"]

# Diccionarios (dict)
paises = {
    "Francia": "París",
    'Reino Unido': 'Londres',
    'EE.UU.': "Nueva York",
    'Colombia': 'Bogotá D.C.',
    'EE.UU.': 'Washington D.C.',
    'Alemania': 'Berlín'
}

# Tuplas (tuple)
coordenadas = (40.4168, -3.7038)  # (latitud, longitud)

# Conjuntos (set)
conjunto = {1, 2, 3, 4, 5}
```

# 2. ¿Qué son las variables?

Las variables son espacios de almacenamiento en la memoria de la computadora que se utilizan para guardar datos. Las variables tienen un nombre y un valor asociado. El nombre de la variable se utiliza para referirse a ese valor en el código. Las variables pueden contener diferentes tipos de datos, como números, cadenas de texto, listas, diccionarios, etc.

# 3. **¿Qué son los tipos de datos?**

Los tipos de datos son categorías que definen el tipo de valor que una variable puede almacenar. En Python, hay varios tipos de datos incorporados, como enteros (int), flotantes (float), cadenas (str), listas (list), diccionarios (dict), tuplas (tuple) y conjuntos (set). Cada tipo de dato tiene sus propias características y métodos asociados.

# 4. **Tipos de variables en Python**

Existen varios tipos de variables en Python, cada uno diseñado para almacenar diferentes tipos de datos. A continuación, se describen algunos de los tipos de variables más comunes:

## 4.1. **Cadena de Texto (str)**: 

Se utiliza para almacenar cadenas de texto. Se define entre comillas
simples o dobles.

### 4.1.1. **Ejemplo**:

``` python
texto = "Hola, mundo!"
```

## 4.2. **Número Decimal (float)**:

Se utiliza para almacenar números decimales. Se define con un punto
decimal.

### 4.2.1. **Ejemplo**:

``` python
numero_decimal = 3.14
```


## 4.3. **Número Entero (int)**:

Se utiliza para almacenar números enteros. No tiene decimales.

### 4.3.1. **Ejemplo**:

``` python
numero_entero = 42
```


## 4.4. **Booleano (bool)**:

Se utiliza para almacenar valores de verdad: `True` o `False`.

### 4.4.1. **Ejemplo**:

``` python
es_verdadero = True
```


## 4.5. **Lista (list)**:

Se utiliza para almacenar una colección de elementos. Se define entre
corchetes `[]`.

### 4.5.1. **Ejemplo**:

``` python
lista = [1, 2, 3, 4, 5]
```


## 4.6. **Diccionario (dict)**:

Se utiliza para almacenar pares clave-valor. Se define entre llaves `{}`.

### 4.6.1. **Ejemplo**:

``` python
diccionario = {
    "nombre": "Juan",
    "edad": 30,
    "ciudad": "Madrid"
}
```

## 4.7. **Tupla (tuple)**: {#7-tupla-tuple}

Se utiliza para almacenar una colección de elementos inmutables. Se define entre paréntesis `()`.

### 4.7.1. **Ejemplo**:

``` python

tupla = (1, 2, 3)
```


## 4.8. **Conjunto (set)**:

Se utiliza para almacenar una colección de elementos únicos. Se define entre llaves `{}`.

### 4.8.1. **Ejemplo**:

```python
conjunto = {1, 2, 3, 4, 5}
```

## 4.9. **Ninguno (None)**:

Se utiliza para representar la ausencia de valor o un valor nulo. Se define como `None`.

### 4.9.1. **Ejemplo**

```python
ninguno = None
```


## 4.10. **Bytes (bytes)**:

Se utiliza para almacenar datos binarios. Se define con un prefijo `b` antes de la cadena.

### 4.10.1. **Ejemplo**:

```python
bytes_datos = b"Hola, mundo!"
```


## 4.11. **Bytearray (bytearray)**:

Se utiliza para almacenar datos binarios mutables. Se define con un prefijo `b` antes de la cadena y se convierte a un objeto `bytearray`.

### 4.11.1. **Ejemplo**:

```python
bytearray_datos = bytearray(b"Hola, mundo!")
```


## 4.12. **Memoryview (memoryview)**: 

Se utiliza para acceder a los datos de un objeto de bytes sin copiarlo. Se define con el constructor `memoryview()`.


### 4.12.1. **Ejemplo**:

```python
memoryview_datos = memoryview(b"Hola, mundo!")
```

## 4.13. **Frozenset (frozenset)**:

```python
frozenset_datos = frozenset([1, 2, 3, 4, 5])
Se utiliza para almacenar una colección de elementos únicos e inmutables. Se define con el constructor `frozenset()`.
```

### 4.13.1. **Ejemplo**:

```python
frozenset_datos = frozenset([1, 2, 3, 4, 5])
```


## 4.14. **Complejo (complex)**:

Se utiliza para almacenar números complejos. Se define con la forma `a + bj`, donde `a` es la parte real y `b` es la parte imaginaria.

### 4.14.1. **Ejemplo**:

```python
numero_complejo = 3 + 4j
```
