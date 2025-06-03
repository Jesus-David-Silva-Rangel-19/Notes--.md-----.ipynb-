# Python: Iteración sobre estructuras de datos

# Iteración sobre estructuras de datos
La iteración es el proceso de recorrer una estructura de datos, como listas, tuplas o diccionarios, para acceder a sus elementos uno por uno. En Python, puedes utilizar bucles `for` o `while` para realizar iteraciones.

## Iteración sobre listas

Las listas son una de las estructuras de datos más comunes en Python. Puedes iterar sobre una lista utilizando un bucle `for` o un bucle `while`.

```python
mi_lista = [10, 20, 30, 40, 50]

# Usando un bucle for
for elemento in mi_lista:
    print("Elemento:", elemento)

# Usando un bucle while
indice = 0
while indice < len(mi_lista):
    print("Elemento:", mi_lista[indice])
    indice += 1
```
> **Descripción:** Este ejemplo muestra cómo iterar sobre una lista utilizando un bucle `for` y un bucle `while`.

**Salida:** La salida será:
```
Elemento: 10
Elemento: 20
Elemento: 30
Elemento: 40
Elemento: 50
```

> **Nota:** Puedes usar la función `enumerate()` para obtener tanto el índice como el valor del elemento durante la iteración.

```python
mi_lista = [10, 20, 30, 40, 50]

# Usando enumerate en un bucle for
for indice, elemento in enumerate(mi_lista):
    print("Índice:", indice, "Elemento:", elemento)
```
> **Descripción:** Este ejemplo muestra cómo usar `enumerate()` para obtener el índice y el valor del elemento durante la iteración.

**Salida:** La salida será:
```python
Índice: 0 Elemento: 10
Índice: 1 Elemento: 20
Índice: 2 Elemento: 30
Índice: 3 Elemento: 40
Índice: 4 Elemento: 50
```

## Iteración sobre diccionarios

Los diccionarios son estructuras de datos que almacenan pares clave-valor. Puedes iterar sobre las claves, los valores o ambos.

**Ejemplos:**

```python
mi_diccionario = {
    "a": 1,
    "b": 2,
    "c": 3
}

# Iterando sobre las claves
for clave in mi_diccionario:
    print("Clave:", clave)

# Iterando sobre los valores
for valor in mi_diccionario.values():
    print("Valor:", valor)

# Iterando sobre los pares clave-valor
for clave, valor in mi_diccionario.items():
    print("Clave:", clave, "Valor:", valor)
```

> **Descripción:** Este ejemplo muestra cómo iterar sobre un diccionario para acceder a las claves, los valores y los pares clave-valor.

**Salida:** La salida será:
```
# Iterando sobre las claves
Clave: a
Clave: b
Clave: c

# Iterando sobre los valores
Valor: 1
Valor: 2
Valor: 3

# Iterando sobre los pares clave-valor
Clave: a Valor: 1
Clave: b Valor: 2
Clave: c Valor: 3
```

## Iteración sobre tuplas

Las tuplas son similares a las listas, pero son inmutables. Puedes iterar sobre una tupla de la misma manera que lo harías con una lista.

**Ejemplos:**

```python
mi_tupla = (10, 20, 30, 40, 50)

# Usando un bucle for
for elemento in mi_tupla:
    print("Elemento:", elemento)

# Usando un bucle while
indice = 0
while indice < len(mi_tupla):
    print("Elemento:", mi_tupla[indice])
    indice += 1
```

> **Descripción:** Este ejemplo muestra cómo iterar sobre una tupla utilizando un bucle `for` y un bucle `while`.

**Salida:** La salida será:
```
Elemento: 10
Elemento: 20
Elemento: 30
Elemento: 40
Elemento: 50
```

### Usando enumerate en una tupla

```python
mi_tupla = (10, 20, 30, 40, 50)

# Usando enumerate en un bucle for
for indice, elemento in enumerate(mi_tupla):
    print("Índice:", indice, "Elemento:", elemento)
```

> **Descripción:** Este ejemplo muestra cómo usar `enumerate()` para obtener el índice y el valor del elemento durante la iteración en una tupla.

**Salida:** La salida será:
```
Índice: 0 Elemento: 10
Índice: 1 Elemento: 20
Índice: 2 Elemento: 30
Índice: 3 Elemento: 40
Índice: 4 Elemento: 50
```

## Iteración sobre conjuntos

Los conjuntos son colecciones no ordenadas de elementos únicos. Puedes iterar sobre un conjunto de manera similar a las listas y tuplas.

```python
mi_conjunto = {10, 20, 30, 40, 50}

# Usando un bucle for
for elemento in mi_conjunto:
    print("Elemento:", elemento)

# Usando un bucle while
indice = 0
while indice < len(mi_conjunto):
    print("Elemento:", list(mi_conjunto)[indice])
    indice += 1
```
> **Descripción:** Este ejemplo muestra cómo iterar sobre un conjunto utilizando un bucle `for` y un bucle `while`.

**Salida:** La salida será:
```
Elemento: 10
Elemento: 20
Elemento: 30
Elemento: 40
Elemento: 50
```

> **Nota:** Los conjuntos no tienen un orden específico, por lo que el orden de los elementos puede variar en cada ejecución

### Usando enumerate en un conjunto

```python
mi_conjunto = {10, 20, 30, 40, 50}

# Usando enumerate en un bucle for
for indice, elemento in enumerate(mi_conjunto):
    print("Índice:", indice, "Elemento:", elemento)
```

> **Descripción:** Este ejemplo muestra cómo usar `enumerate()` para obtener el índice y el valor del elemento durante la iteración en un conjunto.

**Salida:** La salida será:
```
Índice: 0 Elemento: 10
Índice: 1 Elemento: 20
Índice: 2 Elemento: 30
Índice: 3 Elemento: 40
Índice: 4 Elemento: 50
```

## Iteración sobre cadenas
Las cadenas de texto también son iterables en Python. Puedes iterar sobre cada carácter de una cadena utilizando un bucle `for`.

```python
mi_cadena = "Hola, Python"

for caracter in mi_cadena:
    print("Carácter:", caracter)
```
> **Descripción:** Este ejemplo muestra cómo iterar sobre cada carácter de una cadena utilizando un bucle `for`.

**Salida:** La salida será:
```
Carácter: H
Carácter: o
Carácter: l
Carácter: a
Carácter: ,
Carácter:
Carácter:
Carácter: P
Carácter: y
Carácter: t
Carácter: h
Carácter: o
Carácter: n
```

### Usando enumerate en una cadena

```python
mi_cadena = "Hola, Python"
for indice, caracter in enumerate(mi_cadena):
    print("Índice:", indice, "Carácter:", caracter)
```
> **Descripción:** Este ejemplo muestra cómo usar `enumerate()` para obtener el índice y el valor del carácter durante la iteración en una cadena.

**Salida:** La salida será:
```
Índice: 0 Carácter: H
Índice: 1 Carácter: o
Índice: 2 Carácter: l
Índice: 3 Carácter: a
Índice: 4 Carácter: ,
Índice: 5 Carácter:
Índice: 6 Carácter:
Índice: 7 Carácter: P
Índice: 8 Carácter: y
Índice: 9 Carácter: t
Índice: 10 Carácter: h
Índice: 11 Carácter: o
Índice: 12 Carácter: n
```
