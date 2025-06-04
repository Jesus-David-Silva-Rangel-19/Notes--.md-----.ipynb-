# 1. Python: Operaciones Básicas

Este documento cubre las operaciones matemáticas básicas, operaciones aritméticas y de comparación en Python.

Las operaciones matemáticas básicas son fundamentales en programación y se utilizan para realizar cálculos simples. En Python, estas operaciones se pueden realizar utilizando operadores aritméticos.

# 1.1. Operaciones matemáticas aritméticas

Las operaciones matemáticas básicas incluyen suma, resta, multiplicación, división, potencia, división entera y módulo. 

A continuación se presentan ejemplos de cada una de estas operaciones en Python.

## 1.1.1. Suma

La suma es una operación que consiste en agregar dos o más números para obtener un total. En Python, se utiliza el operador `+`.

**Ejemplo:**

```python
# Suma de dos números
a = 5
b = 3

# se usa (+)
suma = a + b

# Imprimir el resultado
print("Suma:", suma)
```

**Salida:**

```
Suma: 8
```

## 1.1.2. Resta

La resta es una operación que consiste en sustraer un número de otro. En Python, se utiliza el operador `-`.

**Ejemplo:**

```python
# Resta de dos números
a = 5
b = 3

# se usa (-)
resta = a - b

# Imprimir el resultado
print("Resta:", resta)
```

**Salida:**

```
Resta: 2
```

## 1.1.3. Multiplicación

La multiplicación es una operación que consiste en sumar un número varias veces. En Python, se utiliza el operador `*`.

**Ejemplo:**

```python
# Multiplicación de dos números
a = 4
b = 5

# se usa (*)
multiplicación = a * b

# Imprimir el resultado
print("Multiplicación:", multiplicación)
```

**Salida:**

```
Multiplicación: 20
```

## 1.1.4. División

La división es una operación que consiste en repartir un número en partes iguales. En Python, se utiliza el operador `/`.

**Ejemplo:**

```python
# División de dos números
a = 6
b = 2

# se usa (/)
división = a / b

# Imprimir el resultado
print("División:", división)
```

**Salida:**

```
División: 3.0
```

## 1.1.5. Potencia

La potencia es una operación que consiste en multiplicar un número por sí mismo varias veces. En Python, se utiliza el operador `**`.

**Ejemplo:**

```python
# Potencia de un número
a = 2
b = 3

# se usa (**)
potencia = a ** b

# Imprimir el resultado
print("Potencia:", potencia)
```

**Salida:**

```
Potencia: 8
```

## 1.1.6. División entera

La división entera consiste en obtener solo la parte entera del cociente al dividir dos números. En Python, se utiliza el operador `//`.

**Ejemplo:**

```python
# División entera de dos números
a = 7
b = 2

# se usa (//)
división_entera = a // b

# Imprimir el resultado
print("División entera:", división_entera)
```

**Salida:**

```
División entera: 3
```

## 1.1.7. Módulo

El módulo es el residuo de una división. En Python, se utiliza el operador `%`.

**Ejemplo:**

```python
# Módulo de dos números
a = 7
b = 2

# se usa (%)
módulo = a % b

# Imprimir el resultado
print("Módulo:", módulo)
```

**Salida:**

```
Módulo: 1
```

## 1.1.8. Tabla de operadores básicos

| Operador | Significado matemático | En programación Python | Ejemplo |
|----------|------------------------|------------------------|---------|
| `+`      | Suma                   | `a + b`                | `5 + 3` |
| `-`      | Resta                  | `a - b`                | `5 - 3` |
| `*`      | Multiplicación         | `a * b`                | `4 * 5` |
| `/`      | División               | `a / b`                | `6 / 2` |
| `**`     | Potencia               | `a ** b`               | `2 ** 3` |
| `//`     | División entera        | `a // b`               | `7 // 2` |
| `%`      | Módulo                 | `a % b`                | `7 % 2` |



# 1.2. Operaciones de comparación

Las operaciones de comparación permiten evaluar relaciones lógicas entre dos valores. Estas expresiones siempre devuelven un valor booleano: `True` o `False`. 

Son fundamentales para la toma de decisiones en programación, especialmente en estructuras como `if`, `while` y bucles de control.A

A continuación se presentan las operaciones de comparación más comunes en Python, junto con ejemplos de uso.


## 1.2.1. Mayor que (`>`)

La operación de comparación "mayor que" se utiliza para verificar si un valor es mayor que otro. En Python, se representa con el símbolo `>`.

**Ejemplo:**

``` python
# Ejemplo de mayor que
a = 5
b = 3

# se usa (>)
mayor_que = a > b

# Imprimir el resultado
print("¿a > b?:", mayor_que)
```

**Salida:**

```
¿a > b?: True
```

## 1.2.2. Menor que (`<`)

La operación de comparación "menor que" se utiliza para verificar si un valor es menor que otro. En Python, se representa con el símbolo `<`.

**Ejemplo:**

``` python
# Ejemplo de menor que
a = 5
b = 3

# se usa (<)
menor_que = a < b

# Imprimir el resultado
print("¿a < b?:", menor_que)
```

**Salida:**

```
¿a < b?: False
```

## 1.2.3. Igual que (`==`)

La operación de comparación "igual que" se utiliza para verificar si dos valores son iguales. En Python, se representa con el símbolo `==`.

``` python
# Ejemplo de igual que
a = 5
b = 5

# se usa (==)
igual_que = a == b

# Imprimir el resultado
print("¿a == b?:", igual_que)
```

**Salida:**

```
¿a == b?: True
```

## 1.2.4. Diferente que (`!=`)

La operación de comparación "diferente que" se utiliza para verificar si dos valores son diferentes. En Python, se representa con el símbolo `!=`.

``` python
# Ejemplo de diferente que
a = 5
b = 3

# se usa (!=)
diferente_que = a != b

# Imprimir el resultado
print("¿a != b?:", diferente_que)
```

**Salida:**

```
¿a != b?: True
```

## 1.2.5. Mayor o igual que (`>=`)

La operación de comparación "mayor o igual que" se utiliza para verificar si un valor es mayor o igual a otro. En Python, se representa con el símbolo `>=`.

**Ejemplo:**

``` python
# Ejemplo de mayor o igual que
a = 10
b = 5

# se usa (>=)
mayor_igual_que = a >= b # se usa (>=)

# Imprimir el resultado
print('Mayor o igual que:', mayor_igual_que)
```

**Salida:**

```
Mayor o igual que: True
```

## 1.2.6. Menor o igual que (`<=`)

La operación de comparación "menor o igual que" se utiliza para verificar si un valor es menor o igual a otro. En Python, se representa con el símbolo `<=`.

**Ejemplo:**

``` python
# Ejemplo de menor o igual que
a = 5
b = 10

# se usa (<=)
menor_igual_que = a <= b

# Imprimir el resultado
print('Menor o igual que:', menor_igual_que)
```

**Salida:**

```
Menor o igual que: True
```


## 1.2.7. Tabla de operadores lógicos

Esta tabla presenta un resumen de la simbología.

| Operador | Significado matemático | En programación Python | Resultado esperado |
|--------|--------------------|--------------------|-------------------------|
| `>` | Mayor que | `a > b` | `True` si `a` \> `b` |
| `<` | Menor que | `a < b` | `True` si `a` \< `b` |
| `==` | Igual que | `a == b` | `True` si `a` es igual a `b` |
| `!=` | Diferente que | `a != b` | `True` si `a` ≠ `b` |
| `>=` | Mayor o igual que | `a >= b` | `True` si `a` ≥ `b` |
| `<=` | Menor o igual que | `a <= b` | `True` si `a` ≤ `b` |


# 1.3. Operaciones lógicas

Las **operaciones lógicas** permiten combinar o evaluar expresiones booleanas. Son fundamentales en estructuras de control como condicionales y bucles. En Python, los operadores lógicos principales son `and`, `or` y `not`.

## 1.3.1. **Y lógico (`and`)**

El operador `and` devuelve `True` si **ambas expresiones** son verdaderas. Se usa cuando se desea que **todas las condiciones** se cumplan.

**Ejemplo:**

```python
# Ejemplo de Y lógico
a = 5
b = 10

# se usa (and)
resultado = a > 0 and b > 0

# Imprimir el resultado
print('Resultado con and:', resultado)
```

**Salida:**

```
Resultado con and: True
```

## 1.3.2. **O lógico (`or`)**

El operador `or` devuelve `True` si **al menos una** de las expresiones es verdadera. Se usa cuando **basta con que una condición** se cumpla.

**Ejemplo:**

```python
# Ejemplo de O lógico
a = -5
b = 10

# se usa (or)
resultado = a > 0 or b > 0

# Imprimir el resultado
print('Resultado con or:', resultado)
```

**Salida:**

```
Resultado con or: True
```

## 1.3.3. **Negación lógica (`not`)**

El operador `not` invierte el valor lógico de una expresión. Si la expresión es `True`, `not` devuelve `False`, y viceversa.

**Ejemplo:**

```python
# Ejemplo de Negación lógica
a = 5

# se usa (not)
resultado = not (a < 0)

# Imprimir el resultado
print('Resultado con not:', resultado)
```

**Salida:**

```
Resultado con not: True
```

## 1.3.4. Tabla de operadores lógicos

| Operador | Descripción                                      | Ejemplo           | Resultado esperado              |
| -------- | ------------------------------------------------ | ----------------- | ------------------------------- |
| `and`    | Verdadero si ambas condiciones son verdaderas    | `a > 0 and b > 0` | `True` si ambas son verdaderas  |
| `or`     | Verdadero si al menos una condición es verdadera | `a > 0 or b > 0`  | `True` si una o ambas lo son    |
| `not`    | Invierte el valor lógico                         | `not (a > 0)`     | `True` si la condición es falsa |

Claro. A continuación se presenta el contenido reorganizado siguiendo el formato estructurado solicitado:

---

# 1.4. Operadores de Asignación en Python

En Python, los **operadores de asignación** permiten almacenar un valor en una variable. Además, existen operadores compuestos que combinan una operación aritmética con la asignación, lo que permite escribir código más conciso y eficiente.

---

## 1.4.1. Asignación simple (`=`)

La asignación simple se utiliza para almacenar un valor en una variable. Se representa con el símbolo `=`.

**Ejemplo:**

```python
# Asignación simple
x = 5

# Imprimir el valor
print('Valor de x:', x)
```

**Salida:**

```
Valor de x: 5
```

---

## 1.4.2. Suma y asignación (`+=`)

La operación `+=` suma el valor de la derecha al valor existente de la variable y actualiza su contenido.

**Ejemplo:**

```python
a = 10
b = 3
a += b  # a = a + b
print('Resultado de a += b:', a)
```

**Salida:**

```
Resultado de a += b: 13
```

---

## 1.4.3. Resta y asignación (`-=`)

La operación `-=` resta el valor de la derecha al valor existente de la variable y actualiza su contenido.

**Ejemplo:**

```python
a = 10
b = 3
a -= b  # a = a - b
print('Resultado de a -= b:', a)
```

**Salida:**

```
Resultado de a -= b: 7
```

---

## 1.4.4. Multiplicación y asignación (`*=`)

La operación `*=` multiplica el valor existente de la variable por el valor de la derecha y actualiza la variable.

**Ejemplo:**

```python
a = 10
b = 3
a *= b  # a = a * b
print('Resultado de a *= b:', a)
```

**Salida:**

```
Resultado de a *= b: 30
```

---

## 1.4.5. División y asignación (`/=`)

La operación `/=` divide el valor existente de la variable por el valor de la derecha y actualiza su contenido. El resultado es de tipo flotante.

**Ejemplo:**

```python
a = 10
b = 3
a /= b  # a = a / b
print('Resultado de a /= b:', a)
```

**Salida:**

```
Resultado de a /= b: 3.3333333333333335
```

---

## 1.4.6. División entera y asignación (`//=`)

La operación `//=` realiza una división entera (sin decimales) y actualiza la variable con el cociente entero.

**Ejemplo:**

```python
a = 10
b = 3
a //= b  # a = a // b
print('Resultado de a //= b:', a)
```

**Salida:**

```
Resultado de a //= b: 3
```

---

## 1.4.7. Módulo y asignación (`%=`)

La operación `%=` calcula el residuo de la división entre el valor actual de la variable y el valor de la derecha, y actualiza la variable.

**Ejemplo:**

```python
a = 10
b = 3
a %= b  # a = a % b
print('Resultado de a %= b:', a)
```

**Salida:**

```
Resultado de a %= b: 1
```

---

## 1.4.8. Exponente y asignación (`**=`)

La operación `**=` eleva la variable a la potencia del valor de la derecha y actualiza su contenido.

**Ejemplo:**

```python
a = 10
b = 3
a **= b  # a = a ** b
print('Resultado de a **= b:', a)
```

**Salida:**

```
Resultado de a **= b: 1000
```

---

## 1.4.9. Tabla de operadores de asignación

| Operador | Operación combinada          | Significado     | Ejemplo   | Resultado esperado         |
| -------- | ---------------------------- | --------------- | --------- | -------------------------- |
| `=`      | Asignación simple            | Asigna un valor | `a = 5`   | `a = 5`                    |
| `+=`     | Suma y asignación            | `a = a + b`     | `a += b`  | Suma y actualiza `a`       |
| `-=`     | Resta y asignación           | `a = a - b`     | `a -= b`  | Resta y actualiza `a`      |
| `*=`     | Multiplicación y asignación  | `a = a * b`     | `a *= b`  | Multiplica y actualiza `a` |
| `/=`     | División y asignación        | `a = a / b`     | `a /= b`  | Divide y actualiza `a`     |
| `//=`    | División entera y asignación | `a = a // b`    | `a //= b` | División entera            |
| `%=`     | Módulo y asignación          | `a = a % b`     | `a %= b`  | Residuo de la división     |
| `**=`    | Potencia y asignación        | `a = a ** b`    | `a **= b` | Potencia y actualiza `a`   |



# 1.5. Resumen de operadores en Python

En Python, existen varios tipos de operadores que permiten realizar diferentes tipos de operaciones. A continuación se presenta un resumen de los principales operadores utilizados en Python, organizados por categorías.

## 1.5.1. 🔹 1. **Operadores Aritméticos**

Permiten realizar operaciones matemáticas básicas.

| Operador | Descripción     | Ejemplo  | Resultado         |
| -------- | --------------- | -------- | ----------------- |
| `+`      | Suma            | `a + b`  | Suma de `a` y `b` |
| `-`      | Resta           | `a - b`  | Diferencia        |
| `*`      | Multiplicación  | `a * b`  | Producto          |
| `/`      | División        | `a / b`  | Cociente (float)  |
| `//`     | División entera | `a // b` | Cociente (entero) |
| `%`      | Módulo          | `a % b`  | Residuo           |
| `**`     | Potencia        | `a ** b` | `a` elevado a `b` |


## 1.5.2. 🔸 2. **Operadores de Asignación**

Asignan valores a variables, con o sin operación previa.

| Operador | Significado        | Equivalencia |
| -------- | ------------------ | ------------ |
| `=`      | Asignación simple  | `a = b`      |
| `+=`     | Suma y asignación  | `a = a + b`  |
| `-=`     | Resta y asignación | `a = a - b`  |
| `*=`     | Multiplicación     | `a = a * b`  |
| `/=`     | División           | `a = a / b`  |
| `//=`    | División entera    | `a = a // b` |
| `%=`     | Módulo             | `a = a % b`  |
| `**=`    | Potencia           | `a = a ** b` |


## 1.5.3. 🔹 3. **Operadores de Comparación**

Comparan dos valores y devuelven un valor booleano.

| Operador | Significado       | Ejemplo  |
| -------- | ----------------- | -------- |
| `==`     | Igual a           | `a == b` |
| `!=`     | Diferente de      | `a != b` |
| `>`      | Mayor que         | `a > b`  |
| `<`      | Menor que         | `a < b`  |
| `>=`     | Mayor o igual que | `a >= b` |
| `<=`     | Menor o igual que | `a <= b` |


## 1.5.4. 🔸 4. **Operadores Lógicos**

Operan sobre valores booleanos (`True` o `False`).

| Operador | Descripción       | Ejemplo            |
| -------- | ----------------- | ------------------ |
| `and`    | Conjunción lógica | `a > 5 and b < 10` |
| `or`     | Disyunción lógica | `a > 5 or b < 10`  |
| `not`    | Negación lógica   | `not a > 5`        |


## 1.5.5. 🔹 5. **Operadores Bit a Bit (Bitwise)**

Operan directamente sobre representaciones binarias de los números.

| Operador | Descripción                   | Ejemplo      | Resultado                              |     |                 |
| -------- | ----------------------------- | ------------ | -------------------------------------- | --- | --------------- |
| `&`      | AND bit a bit                 | `a & b`      | Bits comunes                           |     |                 |
| \`       | \`                            | OR bit a bit | \`a                                    | b\` | Bits combinados |
| `^`      | XOR bit a bit                 | `a ^ b`      | Bits diferentes                        |     |                 |
| `~`      | NOT bit a bit (inverso)       | `~a`         | Complemento                            |     |                 |
| `<<`     | Desplazamiento a la izquierda | `a << 2`     | Desplaza bits 2 lugares a la izquierda |     |                 |
| `>>`     | Desplazamiento a la derecha   | `a >> 2`     | Desplaza bits 2 lugares a la derecha   |     |                 |


## 1.5.6. 🔸 6. **Operadores de Membresía**

Verifican si un valor está presente en una secuencia (como listas, tuplas, cadenas, etc.).

| Operador | Descripción                         | Ejemplo             |
| -------- | ----------------------------------- | ------------------- |
| `in`     | Devuelve `True` si está presente    | `'a' in 'data'`     |
| `not in` | Devuelve `True` si NO está presente | `'x' not in 'data'` |


## 1.5.7. 🔹 7. **Operadores de Identidad**

Evalúan si dos variables se refieren al mismo objeto en memoria.

| Operador | Descripción                         | Ejemplo      |
| -------- | ----------------------------------- | ------------ |
| `is`     | `True` si ambos son el mismo objeto | `a is b`     |
| `is not` | `True` si no son el mismo objeto    | `a is not b` |

