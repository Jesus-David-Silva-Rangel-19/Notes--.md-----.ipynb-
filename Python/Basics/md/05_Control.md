# **Condicionales (if, elif, else)**

# **¿Qué son las estructuras condicionales?**

Son estructuras de control que permiten ejecutar un bloque de código si
una condición es verdadera y otro bloque de código si la condición es
falsa.

------------------------------------------------------------------------

## **¿Cuál es la estructura condicional básica?**

``` python
if condición:
    'bloque de código a ejecutar si la condición es verdadera'
else:
    'bloque de código a ejecutar si la condición es falsa'
```

------------------------------------------------------------------------

## **¿Cuál es la estructura condicional con múltiples opciones?**

``` python
if condición1:
    'bloque de código a ejecutar si la condición1 es verdadera'
elif condición2:
    'bloque de código a ejecutar si la condición2 es verdadera'
else:
    'bloque de código a ejecutar si ninguna de las condiciones anteriores es verdadera'
```

------------------------------------------------------------------------

## **¿Qué es la estructura `if`?**

La estructura `if` es una estructura condicional que permite ejecutar un
bloque de código si una condición es verdadera y otro bloque de código
si la condición es falsa.

------------------------------------------------------------------------

## **¿Cuál es la estructura `elif`?**

La estructura `elif` es una estructura condicional que permite ejecutar
un bloque de código si una condición es verdadera y otro bloque de
código si la condición es falsa.

### **Cuando se usa elif?**

El bloque elif permite evaluar múltiples condiciones. El bloque else
captura todos los casos restantes.

------------------------------------------------------------------------

## **¿Cuál es la estructura `else`?**

La estructura `else` es una estructura condicional que permite ejecutar
un bloque de código si ninguna de las condiciones anteriores es
verdadera.

------------------------------------------------------------------------

# **Cuál es la estructura de iteración?**

``` python
for variable in iterable:
    'bloque de código a ejecutar para cada elemento del iterable'
```

------------------------------------------------------------------------

# **Ejemplo de condicionales en Python**

``` python

edad = 18

# Estructura condicional básica
if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")

# Condicional con múltiples opciones
nota = 85

if nota >= 90:
    print("Excelente")
elif nota >= 70:
    print("Aprobado")
else:
    print("Reprobado")
```

El código del ejemplo anterior utiliza estructuras condicionales en
Python para verificar la edad y la nota de un alumno y mostrar un
mensaje correspondiente.

------------------------------------------------------------------------

``` python
edad = 18

# Estructura condicional básica
if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")

# Condicional con múltiples opciones
nota = 85

if nota >= 90:
    print("Excelente")
elif nota >= 70:
    print("Aprobado")
else:
    print("Reprobado")
```

📌 El bloque elif permite evaluar múltiples condiciones. El bloque else
captura todos los casos restantes.

# **Bucle (for)**

## **¿Qué es un bucle `for`?**

Es una estructura de control que permite iterar sobre una secuencia de
elementos, como una lista o una cadena de caracteres, y ejecutar un
bloque de códig

------------------------------------------------------------------------

``` python
# Iterar sobre una lista
frutas = ["manzana", "pera", "uva"]

for fruta in frutas:
    print("Fruta:", fruta)

# Iterar usando `range()`
for i in range(5):  # 0, 1, 2, 3, 4
    print("Número:", i)

# Iterar con índice y valor usando `enumerate()`
for i, fruta in enumerate(frutas):
    print(f"Índice {i}: {fruta}")
```

    Fruta: manzana
    Fruta: pera
    Fruta: uva
    Número: 0
    Número: 1
    Número: 2
    Número: 3
    Número: 4
    Índice 0: manzana
    Índice 1: pera
    Índice 2: uva

# Bucle (while)

``` python
# Ejecuta mientras la condición sea verdadera
contador = 0

while contador < 5:
    print("Contador:", contador)
    contador += 1
```

⚠️ Precaución: Asegúrese de que la condición cambie, o se generará un
bucle infinito.

# Instrucciones (break, continue y pass)

``` python
# break: termina el bucle
for numero in range(10):
    if numero == 5:
        break # termina el bucle
    print("Número con break:", numero)

# continue: salta a la siguiente iteración
for numero in range(5):
    if numero == 2:
        continue # salta el 2
    print("Número con continue:", numero)

# pass: no hace nada (bloque vacío)
for letra in "ABC":
    pass  # útil como marcador de posición
```

# Operadores de comparación y lógicos

``` python
# Comparaciones
print(5 == 5)   # Igual
print(5 != 3)   # Distinto
print(7 > 4)    # Mayor
print(2 <= 2)   # Menor o igual

# Lógicos
a = True
b = False
print(a and b)  # False
print(a or b)   # True
print(not a)    # False
```