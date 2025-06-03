# Python: Variables

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

# ¿Qué son las variables?

Las variables son espacios de almacenamiento en la memoria de la computadora que se utilizan para guardar datos. Las variables tienen un nombre y un valor asociado. El nombre de la variable se utiliza para referirse a ese valor en el código. Las variables pueden contener diferentes tipos de datos, como números, cadenas de texto, listas, diccionarios, etc.

# **¿Qué son los tipos de datos?**

Los tipos de datos son categorías que definen el tipo de valor que una variable puede almacenar. En Python, hay varios tipos de datos incorporados, como enteros (int), flotantes (float), cadenas (str), listas (list), diccionarios (dict), tuplas (tuple) y conjuntos (set). Cada tipo de dato tiene sus propias características y métodos asociados.

# **Tipos de variables en Python**

Existen varios tipos de variables en Python, cada uno diseñado para almacenar diferentes tipos de datos. A continuación, se describen algunos de los tipos de variables más comunes:

## 1. **Cadena de Texto (str)**: 

Se utiliza para almacenar cadenas de texto. Se define entre comillas
simples o dobles.

### **Ejemplo**:

``` python
texto = "Hola, mundo!"
```

## 2. **Número Decimal (float)**:

Se utiliza para almacenar números decimales. Se define con un punto
decimal.

### **Ejemplo**:

``` python
numero_decimal = 3.14
```


## 3. **Número Entero (int)**:

Se utiliza para almacenar números enteros. No tiene decimales.

### **Ejemplo**:

``` python
numero_entero = 42
```


## 4. **Booleano (bool)**:

Se utiliza para almacenar valores de verdad: `True` o `False`.

### **Ejemplo**:

``` python
es_verdadero = True
```


## 5. **Lista (list)**:

Se utiliza para almacenar una colección de elementos. Se define entre
corchetes `[]`.

### **Ejemplo**:

``` python
lista = [1, 2, 3, 4, 5]
```


## 6. **Diccionario (dict)**:

Se utiliza para almacenar pares clave-valor. Se define entre llaves
`{}`.

### **Ejemplo**:

``` python
diccionario = {
    "nombre": "Juan",
    "edad": 30,
    "ciudad": "Madrid"
}
```

## 7. **Tupla (tuple)**: {#7-tupla-tuple}

Se utiliza para almacenar una colección de elementos inmutables. Se define entre paréntesis `()`.

### **Ejemplo**:

``` python

tupla = (1, 2, 3)
```


## 8. **Conjunto (set)**:

Se utiliza para almacenar una colección de elementos únicos. Se define entre llaves `{}`.

### **Ejemplo**:

```python
conjunto = {1, 2, 3, 4, 5}
```

## 9. **Ninguno (None)**:

Se utiliza para representar la ausencia de valor o un valor nulo. Se define como `None`.

### **Ejemplo**

```python
ninguno = None
```


## 10. **Bytes (bytes)**:

Se utiliza para almacenar datos binarios. Se define con un prefijo `b` antes de la cadena.

### **Ejemplo**:

```python
bytes_datos = b"Hola, mundo!"
```


## 11. **Bytearray (bytearray)**:

Se utiliza para almacenar datos binarios mutables. Se define con un prefijo `b` antes de la cadena y se convierte a un objeto `bytearray`.

### **Ejemplo**:

```python
bytearray_datos = bytearray(b"Hola, mundo!")
```


## 12. **Memoryview (memoryview)**: 

Se utiliza para acceder a los datos de un objeto de bytes sin copiarlo. Se define con el constructor `memoryview()`.


### **Ejemplo**:

```python
memoryview_datos = memoryview(b"Hola, mundo!")
```

## 13. **Frozenset (frozenset)**:

```python
frozenset_datos = frozenset([1, 2, 3, 4, 5])
Se utiliza para almacenar una colección de elementos únicos e inmutables. Se define con el constructor `frozenset()`.
```

### **Ejemplo**:

```python
frozenset_datos = frozenset([1, 2, 3, 4, 5])
```


## 14. **Complejo (complex)**:

Se utiliza para almacenar números complejos. Se define con la forma `a + bj`, donde `a` es la parte real y `b` es la parte imaginaria.

### **Ejemplo**:

```python
numero_complejo = 3 + 4j
```
