# Operaciones básicas

``` python
a = 10
b = 3

suma = a + b # se usa (+)
resta = a -b # se usa (-)
multiplicación = a * b # se usa (*)
división = a / b # se usa (/)
potencia = a ** 2 # se usa (**)
división_entera = a // 3 # se usa (//)
módulo = a % 3 # se usa (%)

print('Suma:', suma)
print('Resta:', resta)
print('Multiplicación:', multiplicación)
print('División:', división)
print('potencia', potencia)
print('División entera:', división_entera)
print('Módulo:', módulo)
```

# **¿Cuáles son y qué son las operaciones básicas?**

- **Suma:** Se representa con el símbolo (+) y permite agregar dos o más
  números.  
- **Resta:** Se representa con el símbolo (-) y permite sustraer un
  número de otro.  
- **Multiplicación:** Se representa con los símbolos ( \times ), ( \cdot
  ) o mediante omisión del signo. En Python, se usa `*`.  
- **División:** Se representa con el símbolo ( \div ) o como fracción (
  \frac{a}{b} ). En Python, se usa `/`.  
- **Potencia:** Se representa con el símbolo ( a^b ). En Python, se usa
  `**`.  
- **División entera:** Devuelve solo la parte entera del cociente. En
  Python, se representa con `//`.  
- **Módulo:** Devuelve el residuo de una división. Se representa con (
  \bmod ) o `%` en Python.



## **¿Qué es la suma?**

La suma es una operación matemática que consiste en agregar dos o más
números para obtener un total. Se representa con el símbolo (+).  
Por ejemplo, si tenemos (2) y (3), la suma sería:

2 + 3 = 5

4 + 5 = 9



## **¿Qué es la resta?**

La resta es una operación matemática que consiste en quitar un número de
otro. Se representa con el símbolo (-).  
Por ejemplo, si tenemos (5) y le restamos (2), la operación sería:

5 − 2 = 3

4 − 5 = −1



## **¿Qué es la multiplicación?**

La multiplicación consiste en sumar un número varias veces. Se
representa con ( \cdot ) o ( \times ); en programación se utiliza `*`.  
Por ejemplo, si tenemos (2) y lo multiplicamos por (3):

2 ⋅ 3 = 6

4 × 5 = 20



## **¿Qué es la división?**

La división es una operación que consiste en repartir un número en
partes iguales. Se representa con ( \div ) o como fracción.  
Por ejemplo, si dividimos (6) entre (2):

6 ÷ 2 = 3

$$\frac{4}{5} = 0.8$$



## **¿Qué es la potencia?**

La potencia es una operación que consiste en multiplicar un número por
sí mismo varias veces. Se representa como ( a^b ); en Python se escribe
`a ** b`.  
Por ejemplo, si elevamos (2) a la potencia de (3):

2<sup>3</sup> = 8

4<sup>2</sup> = 16



## **¿Qué es la división entera?**

La división entera consiste en obtener solo la parte entera del cociente
al dividir dos números. En Python, se representa con `//`.  
Por ejemplo:

7 ÷ 3 = 2.33  ⇒  7//3 = 2

4//3 = 1



## **¿Qué es el módulo?**

El módulo o residuo es el resultado restante de una división. En
matemáticas se representa con ( \bmod ); en Python con `%`.  
Por ejemplo:

7 mod  3 = 1

4 mod  3 = 1



# **Operaciones básicas en Python**

A continuación, se muestran las operaciones matemáticas básicas
utilizando el lenguaje de programación Python.



## **Suma**

``` python
# Suma de dos números
a = 2
b = 3
resultado = a + b
print(resultado)  # Salida: 5
```



## **Resta**

``` python
# Resta de dos números
a = 5
b = 2
resultado = a - b
print(resultado)  # Salida: 3
```



## **Multiplicación**

``` python
# Multiplicación de dos números
a = 4
b = 5
resultado = a * b
print(resultado)  # Salida: 20
```



## **División**

``` python
# División de dos números
a = 6
b = 2
resultado = a / b
print(resultado)  # Salida: 3.0
```



# **División entera**

``` python
# División entera de dos números
a = 7
b = 2
resultado = a // b
print(resultado)  # Salida: 3
```



# **Módulo**

``` python
# Módulo de dos números
a = 7
b = 2
resultado = a % b
print(resultado)  # Salida: 1
```



# **Potencia**

``` python
# Potencia de un número
a = 2
b = 3
resultado = a ** b
print(resultado)  # Salida: 8
```

# **Operaciones de comparación**

``` python
mayor_que = a > b # se usa (>)
menor_que = a < b # se usa (<)
igual_que = a == b # se usa (==)
diferente_que = a != b # se usa (!=)
mayor_igual_que = a >= b # se usa (>=)
menor_igual_que = a <= b # se usa (<=)

print('----------------------------------')
print('Operaciones de comparación:')
print('----------------------------------')
print('Mayor que:', mayor_que)
print('Menor que:', menor_que)
print('Igual que:', igual_que)
print('Diferente que:', diferente_que)
print('Mayor o igual que:', mayor_igual_que)
print('Menor o igual que:', menor_igual_que)
print('----------------------------------')
```

# **¿Qué son las operaciones de comparación?**

Las operaciones de comparación permiten evaluar relaciones lógicas entre
dos valores. Estas expresiones siempre devuelven un valor booleano:
`True` o `False`. Son fundamentales para la toma de decisiones en
programación, especialmente en estructuras como `if`, `while` y bucles
de control.

## **Ejemplo general:**

``` python
a = 10
b = 3
if a > b:
    print('a es mayor que b')
else:
    print('a no es mayor que b')
```

En este ejemplo, la operación de comparación `a > b` devuelve True, por
lo que se ejecuta la primera parte del bloque if.}



## **Tabla de simbología**

Esta tabla presenta un resumen de la simbología.

| Operador | Significado matemático | En programación Python | Resultado esperado |
|--------|--------------------|--------------------|-------------------------|
| `>` | Mayor que | `a > b` | `True` si `a` \> `b` |
| `<` | Menor que | `a < b` | `True` si `a` \< `b` |
| `==` | Igual que | `a == b` | `True` si `a` es igual a `b` |
| `!=` | Diferente que | `a != b` | `True` si `a` ≠ `b` |
| `>=` | Mayor o igual que | `a >= b` | `True` si `a` ≥ `b` |
| `<=` | Menor o igual que | `a <= b` | `True` si `a` ≤ `b` |



## **Mayor que (\>):**

**Matemáticamente:** Se usa para expresar que un número es mayor que
otro. <br> **En Python:** Evalúa si el valor de la izquierda es mayor
que el de la derecha.

``` python
a = 7
b = 5
print("¿a > b?", a > b)  # True, porque 7 es mayor que 5
```



## **Menor que (\<):**

**Matemáticamente:** Se usa para expresar que un número es menor que
otro. <br> **En Python:** Evalúa si el valor de la izquierda es menor
que el de la derecha.

``` python

a = 2
b = 6

print("¿a < b?", a < b)  # True, porque 2 es menor que 6
```



## **Igual que (==):**

**Matemáticamente:** Se usa para afirmar que dos cantidades son iguales.
<br> **En Python:** Compara si ambos valores son exactamente iguales.

``` python

a = 4
b = 4
print("¿a == b?", a == b)  # True, porque ambos son iguales
```



## **Diferente que (!=):**

**Matemáticamente:** Se usa para indicar que dos cantidades no son
iguales. <br> **En Python:** Evalúa si los valores son distintos.

``` python

a = 8
b = 10
print("¿a != b?", a != b)  # True, porque 8 es diferente de 10
```



## **Mayor o igual que (\>=):**

**Matemáticamente:** Indica que un número es mayor o igual a otro. <br>
**En Python:** Devuelve `True` si el valor de la izquierda es mayor o
igual al de la derecha.

``` python

a = 10
b = 3
mayor_igual_que = a >= b # se usa (>=)
print('Mayor o igual que:', mayor_igual_que)
```



## **Menor o igual que (\<=):**

**Matemáticamente:** Indica que un número es menor o igual a otro. <br>
**En Python:** Devuelve `True` si el valor de la izquierda es menor o
igual al de la derecha.

``` python
a = 10
b = 3
menor_igual_que = a <= b # se usa (<=)
print('Menor o igual que:', menor_igual_que)
```



# Operaciones lógicas

``` python
a = True
b = False

print('----------------------------------')
print('Operaciones lógicas:')
print('----------------------------------')
print('a and b:', a and b) # se usa (and)
print('a or b:', a or b) # se usa (or)
print('not a:', not a) # se usa (not)
print('not b:', not b) # se usa (not)
print('----------------------------------')
```

# **¿Qué son las operaciones lógicas?**

Las operaciones lógicas son operaciones que se realizan sobre valores
booleanos (True o False).

Las operaciones lógicas más comunes son:

- **and**: devuelve True si ambos operandos son True.
- **or**: devuelve True si al menos uno de los operandos es True.\|
- **not**: devuelve True si el operando es False y viceversa.
- **xor**: devuelve True si uno de los operandos es True y el otro es
  False.
- **is**: devuelve True si ambos operandos son el mismo objeto.
- **is not**: devuelve True si ambos operandos no son el mismo objeto.



# **Ejemplos de operaciones lógicas con Python**

## **Operador lógico AND**

``` python

print('----------------------------------')
print('Operador lógico AND:')
print('----------------------------------')
print('True and True:', True and True) # True
print('True and False:', True and False) # False
print('False and True:', False and True) # False
print('False and False:', False and False) # False
print('----------------------------------')
```



## **Operador lógico OR**

``` python
print('----------------------------------')
print('Operador lógico OR:')
print('----------------------------------')
print('True or True:', True or True) # True
print('True or False:', True or False) # True
print('False or True:', False or True) # True
print('False or False:', False or False) # False
print('----------------------------------')
```



## **Operador lógico NOT**

``` python

print('----------------------------------')
print('Operador lógico NOT:')
print('----------------------------------')
print('not True:', not True) # False
print('not False:', not False) # True
print('----------------------------------')
```



## **Operador lógico XOR**

``` python
print('----------------------------------')
print('Operador lógico XOR:')
print('----------------------------------')
print('True ^ True:', True ^ True) # False
print('True ^ False:', True ^ False) # True
print('False ^ True:', False ^ True) # True
print('False ^ False:', False ^ False) # False
print('----------------------------------')
```



## **Operador lógico NAND**

``` python
print('----------------------------------')
print('Operador lógico NAND:')
print('----------------------------------')
print('True and True:', not (True and True)) # False
print('True and False:', not (True and False)) # True
print('False and True:', not (False and True)) # True
print('False and False:', not (False and False)) # True
print('----------------------------------')
```



## **Operador lógico NOR**

``` python
print('----------------------------------')
print('Operador lógico NOR:')
print('----------------------------------')
print('True or True:', not (True or True)) # False
print('True or False:', not (True or False)) # False
print('False or True:', not (False or True)) # False
print('False or False:', not (False or False)) # True
print('----------------------------------')
```



## **Operador lógico XNOR**

``` python
print('----------------------------------')
print('Operador lógico XNOR:')
print('----------------------------------')
print('True ^ True:', not (True ^ True)) # True
print('True ^ False:', not (True ^ False)) # False
print('False ^ True:', not (False ^ True)) # False
print('False ^ False:', not (False ^ False)) # True
print('----------------------------------')
```



## **Operador lógico IMPLIES**

``` python

print('----------------------------------')
print('Operador lógico IMPLIES:')
print('----------------------------------')
print('True => True:', not True or True) # True
print('True => False:', not True or False) # False
print('False => True:', not False or True) # True
print('False => False:', not False or False) # True
print('----------------------------------')
```



## **Operador lógico BICONDITIONAL**

``` python

print('----------------------------------')
print('Operador lógico BICONDITIONAL:')
print('----------------------------------')
print('True <=> True:', True == True) # True
print('True <=> False:', True == False) # False
print('False <=> True:', False == True) # False
print('False <=> False:', False == False) # True
print('----------------------------------')
```



## **Operador lógico NOT IMPLIES**

``` python
print('----------------------------------')
print('Operador lógico NOT IMPLIES:')
print('----------------------------------')
print('True => True:', not True or True) # True
print('True => False:', not True or False) # False
print('False => True:', not False or True) # True
print('False => False:', not False or False) # True
print('----------------------------------')
```



## **Operador lógico NOT BICONDITIONAL**

``` python
print('----------------------------------')
print('Operador lógico NOT BICONDITIONAL:')
print('----------------------------------')
print('True <=> True:', not (True == True)) # False
print('True <=> False:', not (True == False)) # True
print('False <=> True:', not (False == True)) # True
print('False <=> False:', not (False == False)) # False
print('----------------------------------')
```



# **Operaciones de asignación**

``` python
a = 10
b = 3

a += b # se usa (+=)
a -= b # se usa (-=)
a *= b # se usa (*=)
a /= b # se usa (/=)
a **= b # se usa (**=)
a //= b # se usa (//=)
a %= b # se usa (%=)

print('----------------------------------')
print('Operaciones de asignación:')
print('----------------------------------')
print('a += b:', a)
print('a -= b:', a)
print('a *= b:', a)
print('a /= b:', a)
print('a **= b:', a)
print('a //= b:', a)
print('a %= b:', a)
print('----------------------------------')
```

### Operaciones de Asignación en Python

En Python, las **operaciones de asignación** permiten realizar una
operación aritmética sobre una variable y asignar el resultado de esa
operación a la misma variable de manera concisa. Estas operaciones son
útiles para modificar valores de forma eficiente, evitando la necesidad
de escribir la variable en ambas partes de la operación.

#### Tipos de Operaciones de Asignación

Existen varias operaciones de asignación, que combinan una operación
aritmética con la asignación del valor resultante:

1.  **Suma y asignación (`+=`)**
    - **Descripción:** Suma el valor de la derecha a la variable de la
      izquierda y asigna el resultado a la variable de la izquierda.

    - **Ejemplo:**

      ``` python
      a = 10
      b = 3
      a += b  # a = a + b
      print(a)  # Salida: 13
      ```
2.  **Resta y asignación (`-=`)**
    - **Descripción:** Resta el valor de la derecha a la variable de la
      izquierda y asigna el resultado a la variable de la izquierda.

    - **Ejemplo:**

      ``` python
      a = 10
      b = 3
      a -= b  # a = a - b
      print(a)  # Salida: 7
      ```
3.  **Multiplicación y asignación (`*=`)**
    - **Descripción:** Multiplica el valor de la derecha por la variable
      de la izquierda y asigna el resultado a la variable de la
      izquierda.

    - **Ejemplo:**

      ``` python
      a = 10
      b = 3
      a *= b  # a = a * b
      print(a)  # Salida: 30
      ```
4.  **División y asignación (`/=`)**
    - **Descripción:** Divide la variable de la izquierda por el valor
      de la derecha y asigna el resultado a la variable de la izquierda.

    - **Ejemplo:**

      ``` python
      a = 10
      b = 3
      a /= b  # a = a / b
      print(a)  # Salida: 3.3333...
      ```
5.  **Exponente y asignación (`**=`)**
    - **Descripción:** Eleva la variable de la izquierda a la potencia
      del valor de la derecha y asigna el resultado a la variable de la
      izquierda.

    - **Ejemplo:**

      ``` python
      a = 10
      b = 3
      a **= b  # a = a ** b
      print(a)  # Salida: 1000
      ```
6.  **División entera y asignación (`//=`)**
    - **Descripción:** Realiza una división entera de la variable de la
      izquierda por el valor de la derecha y asigna el resultado a la
      variable de la izquierda.

    - **Ejemplo:**

      ``` python
      a = 10
      b = 3
      a //= b  # a = a // b
      print(a)  # Salida: 3
      ```
7.  **Módulo y asignación (`%=`)**
    - **Descripción:** Calcula el residuo de la división de la variable
      de la izquierda entre el valor de la derecha y asigna el resultado
      a la variable de la izquierda.

    - **Ejemplo:**

      ``` python
      a = 10
      b = 3
      a %= b  # a = a % b
      print(a)  # Salida: 1
      ```

### Ejemplo completo

El siguiente código muestra el uso de las operaciones de asignación
mencionadas:

```python 
a = 10
b = 3

a += b  # a = a + b
a -= b  # a = a - b
a *= b  # a = a * b
a /= b  # a = a / b
a **= b  # a = a ** b
a //= b  # a = a // b
a %= b  # a = a % b

print('----------------------------------')
print('Operaciones de asignación:')
print('----------------------------------')
print('a += b:', a)
print('a -= b:', a)
print('a *= b:', a)
print('a /= b:', a)
print('a **= b:', a)
print('a //= b:', a)
print('a %= b:', a)
print('----------------------------------')
```


Las operaciones de asignación son aquellas que nos permiten asignar un
valor a una variable. En Python, la operación de asignación se realiza
con el símbolo `=`.

## **Tipos de operaciones de asignación?**

Las operaciones de asignación pueden ser simples o compuestas. Las
operaciones de asignación simples son aquellas que asignan un valor a
una variable, mientras que las operaciones de asignación compuestas son
aquellas que combinan una operación aritmética con la asignación. Por
ejemplo, la operación `+=` suma un valor a una variable y luego asigna
el resultado a esa misma variable. Otras operaciones de asignación
compuestas incluyen `-=`, `*=`, `/=`, `//=`, `%=`, `**=`, y `&=`, entre
otras.

## **Ejemplos con Python**

``` python
# Asignación de un valor a una variable
x = 5
y = 10

# Asignación de una expresión a una variable
z = x + y

# Asignación de una cadena a una variable
nombre = "Juan"

# Asignación de una lista a una variable
numeros = [1, 2, 3, 4, 5]

# Asignación de un diccionario a una variable
persona = {"nombre": "Juan", "edad": 30}

# Asignación de un valor booleano a una variable
es_mayor_de_edad = True

# Asignación de una tupla a una variable
coordenadas = (10, 20)

# Asignación de un conjunto a una variable
conjunto = {1, 2, 3, 4, 5}

# Asignación de un valor nulo a una variable
nulo = None

# Asignación de una variable a otra
copia = x

# Asignación de una variable a sí misma
x += 1

# Asignación de una variable a una expresión
x = x * 2

# Asignación de una variable a una función
def suma(a, b):
    return a + b
resultado = suma(x, y)

# Asignación de una variable a una función lambda
suma_lambda = lambda a, b: a + b
resultado_lambda = suma_lambda(x, y)

# Asignación de una variable a una lista por comprensión
cuadrados = [i**2 for i in range(10)]

# Asignación de una variable a un diccionario por comprensión
cuadrados_dict = {i: i**2 for i in range(10)}

# Asignación de una variable a un conjunto por comprensión
cuadrados_set = {i**2 for i in range(10)}

# Asignación de una variable a una cadena por comprensión
cadena = ''.join(str(i) for i in range(10))

# Asignación de una variable a un generador
generador = (i**2 for i in range(10))
```



### **Que hace la asignación (`+=`)**

La asignación `+=` suma el valor de la variable a la derecha al valor de
la variable a la izquierda y asigna el resultado a la variable de la
izquierda. Por ejemplo, si `a = 10` y `b = 3`, entonces `a += b` es
equivalente a `a = a + b`, lo que significa que `a` se convierte en
`13`.



### **Que hace la asignación (`-=`)**

La asignación `-=` resta el valor de la variable a la derecha al valor
de la variable a la izquierda y asigna el resultado a la variable de la
izquierda. Por ejemplo, si `a = 10` y `b = 3`, entonces `a -= b` es
equivalente a `a = a - b`, lo que significa que `a` se convierte en `7`.



### **Que hace la asignación (`*=`)**

La asignación `*=` multiplica el valor de la variable a la derecha por
el valor de la variable a la izquierda y asigna el resultado a la
variable de la izquierda. Por ejemplo, si `a = 10` y `b = 3`, entonces
`a *= b` es equivalente a `a = a * b`, lo que significa que `a` se
convierte en `30`.



### **Que hace la asignación (`/=`)**

La asignación `/=` divide el valor de la variable a la izquierda por el
valor de la variable a la derecha y asigna el resultado a la variable de
la izquierda. Por ejemplo, si `a = 10` y `b = 3`, entonces `a /= b` es
equivalente a `a = a / b`, lo que significa que `a` se convierte en
`3.3333333333333335`.



### **Que hace la asignación (`**=`)**

La asignación `**=` eleva el valor de la variable a la izquierda a la
potencia del valor de la variable a la derecha y asigna el resultado a
la variable de la izquierda. Por ejemplo, si `a = 10` y `b = 3`,
entonces `a **= b` es equivalente a `a = a ** b`, lo que significa que
`a` se convierte en `1000`.



### **Que hace la asignación (`//=`)**

La asignación `//=` divide el valor de la variable a la izquierda por el
valor de la variable a la derecha y asigna el resultado a la variable de
la izquierda, redondeando hacia abajo al entero más cercano. Por
ejemplo, si `a = 10` y `b = 3`, entonces `a //= b` es equivalente a
`a = a // b`, lo que significa que `a` se convierte en `3`.



### **Que hace la asignación (`%=`)**

La asignación `%=` calcula el resto de la división del valor de la
variable a la izquierda por el valor de la variable a la derecha y
asigna el resultado a la variable de la izquierda. Por ejemplo, si
`a = 10` y `b = 3`, entonces `a %= b` es equivalente a `a = a % b`, lo
que significa que `a` se convierte en `1`.



### **Que hace la asignación (`=`)**

La asignación `=` asigna el valor de la variable a la derecha a la
variable a la izquierda.

Por ejemplo, si `a = 10` y `b = 3`, entonces `a = b` es equivalente a
`a = 3`, lo que significa que `a` se convierte en `3`.



### **Que hace la asignación (`==`)**

La asignación `==` compara si el valor de la variable a la izquierda es
igual al valor de la variable a la derecha. Por ejemplo, si `a = 10` y
`b = 3`, entonces `a == b` es equivalente a `10 == 3`, lo que significa
que el resultado es `False`.



### **Que hace la asignación (`!=`)**

La asignación `!=` compara si el valor de la variable a la izquierda es
diferente al valor de la variable a la derecha. Por ejemplo, si `a = 10`
y `b = 3`, entonces `a != b` es equivalente a `10 != 3`, lo que
significa que el resultado es `True`.



### **Que hace la asignación (`>`)**

La asignación `>` compara si el valor de la variable a la izquierda es
mayor que el valor de la variable a la derecha. Por ejemplo, si `a = 10`
y `b = 3`, entonces `a > b` es equivalente a `10 > 3`, lo que significa
que el resultado es `True`.



### **Que hace la asignación (`<`)**

La asignación `<` compara si el valor de la variable a la izquierda es
menor que el valor de la variable a la derecha. Por ejemplo, si `a = 10`
y `b = 3`, entonces `a < b` es equivalente a `10 < 3`, lo que significa
que el resultado es `False`.



### **Que hace la asignación (`>=`)**

La asignación `>=` compara si el valor de la variable a la izquierda es
mayor o igual que el valor de la variable a la derecha. Por ejemplo, si
`a = 10` y `b = 3`, entonces `a >= b` es equivalente a `10 >= 3`, lo que
significa que el resultado es `True`.



### **Que hace la asignación (`<=`)**

La asignación `<=` compara si el valor de la variable a la izquierda es
menor o igual que el valor de la variable a la derecha. Por ejemplo, si
`a = 10` y `b = 3`, entonces `a <= b` es equivalente a `10 <= 3`, lo que
significa que el resultado es `False`.



### **Que hace la asignación (`and`)**

La asignación `and` compara si ambas variables son verdaderas. Por
ejemplo, si `a = True` y `b = False`, entonces `a and b` es equivalente
a `True and False`, lo que significa que el resultado es `False`.



### **Que hace la asignación (`or`)**

La asignación `or` compara si al menos una de las variables es
verdadera. Por ejemplo, si `a = True` y `b = False`, entonces `a or b`
es equivalente a `True or False`, lo que significa que el resultado es
`True`.



### **Que hace la asignación (`not`)**

La asignación `not` invierte el valor de la variable.

Por ejemplo, si `a = True`, entonces `not a` es equivalente a
`not True`, lo que significa que el resultado es `False`.



### **Que hace la asignación (`is`)**

La asignación `is` compara si ambas variables son el mismo objeto en
memoria. Por ejemplo, si `a = [1, 2, 3]` y `b = a`, entonces `a is b` es
equivalente a `a is a`, lo que significa que el resultado es `True`.



### **Que hace la asignación (`is not`)**

La asignación `is not` compara si ambas variables no son el mismo objeto
en memoria. Por ejemplo, si `a = [1, 2, 3]` y `b = [1, 2, 3]`, entonces
`a is not b` es equivalente a `a is not a`, lo que significa que el
resultado es `True`.



### **Que hace la asignación (`in`)**

La asignación `in` compara si un elemento está dentro de una lista,
tupla o cadena. Por ejemplo, si `a = [1, 2, 3]` y `b = 2`, entonces
`b in a` es equivalente a `2 in [1, 2, 3]`, lo que significa que el
resultado es `True`.



### **Que hace la asignación (`not in`)**

La asignación `not in` compara si un elemento no está dentro de una
lista, tupla o cadena. Por ejemplo, si `a = [1, 2, 3]` y `b = 4`,
entonces `b not in a` es equivalente a `4 not in [1, 2, 3]`, lo que
significa que el resultado es `True`.



### **Que hace la asignación (`isinstance`)**

La asignación `isinstance` compara si una variable es de un tipo
específico. Por ejemplo, si `a = 10`, entonces `isinstance(a, int)` es
equivalente a `isinstance(10, int)`, lo que significa que el resultado
es `True`.



### **Que hace la asignación (`issubclass`)**

La asignación `issubclass` compara si una clase es una subclase de otra
clase. Por ejemplo, si `class A: pass` y `class B(A): pass`, entonces
`issubclass(B, A)` es equivalente a `issubclass(B, A)`, lo que significa
que el resultado es `True`.



### **Que hace la asignación (`callable`)**

La asignación `callable` compara si una variable es callable (es decir,
si se puede llamar como una función). Por ejemplo, si
`def func(): pass`, entonces `callable(func)` es equivalente a
`callable(func)`, lo que significa que el resultado es `True`.



### **Que hace la asignación (`len`)**

La asignación `len` devuelve la longitud de una lista, tupla o cadena.
Por ejemplo, si `a = [1, 2, 3]`, entonces `len(a)` es equivalente a
`len([1, 2, 3])`, lo que significa que el resultado es `3`.



### **Que hace la asignación (`max`)**

La asignación `max` devuelve el valor máximo de una lista, tupla o
conjunto. Por ejemplo, si `a = [1, 2, 3]`, entonces `max(a)` es
equivalente a `max([1, 2, 3])`, lo que significa que el resultado es
`3`.



### **Que hace la asignación (`min`)**

La asignación `min` devuelve el valor mínimo de una lista, tupla o
conjunto. Por ejemplo, si `a = [1, 2, 3]`, entonces `min(a)` es
equivalente a `min([1, 2, 3])`, lo que significa que el resultado es
`1`.



# **Operaciones de identidad**

``` python
a = [1, 2, 3]
b = a
c = a.copy()

print('----------------------------------')
print('Operaciones de identidad:')
print('----------------------------------')
print('a is b:', a is b) # se usa (is)
print('a is not b:', a is not b) # se usa (is not)
print('a is c:', a is c) # se usa (is)
print('a is not c:', a is not c) # se usa (is not)
print('----------------------------------')
```

# **¿Qué son las operaciones de identidad**

Las operaciones de identidad son aquellas que nos permiten comparar si
dos objetos son el mismo objeto en memoria. En Python, los objetos son
identificados por su dirección de memoria, y las operaciones de
identidad nos permiten verificar si dos variables apuntan al mismo
objeto o no.



## **¿Explicación de las operaciones de identidad?**

- `is`: Esta operación devuelve `True` si dos variables apuntan al mismo
  objeto en memoria. En otras palabras, verifica si ambas variables son
  el mismo objeto.
- `is not`: Esta operación devuelve `True` si dos variables no apuntan
  al mismo objeto en memoria. Es decir, verifica si ambas variables son
  objetos diferentes.
- `a is b`: Verifica si `a` y `b` son el mismo objeto en memoria.
- `a is not b`: Verifica si `a` y `b` son objetos diferentes en memoria.
- `a is c`: Verifica si `a` y `c` son el mismo objeto en memoria.
- `a is not c`: Verifica si `a` y `c` son objetos diferentes en memoria.



## **Operación (`is`)**

La operación `is` se utiliza para verificar si dos variables apuntan al
mismo objeto en memoria. Si ambas variables son el mismo objeto, la
operación devuelve `True`, de lo contrario, devuelve `False`.

### **Ejemplo:**

``` python
a = [1, 2, 3]
b = a

c = a.copy()
print(a is b)  # True, porque 'b' es una referencia al mismo objeto que 'a'
print(a is c)  # False, porque 'c' es una copia de 'a', no el mismo objeto
```



## **Operación (`is not`)**

La operación `is not` se utiliza para verificar si dos variables no
apuntan al mismo objeto en memoria. Si ambas variables son objetos
diferentes, la operación devuelve `True`, de lo contrario, devuelve
`False`.

### **Ejemplo:**

``` python

a = [1, 2, 3]
b = a

c = a.copy()
print(a is not b)  # False, porque 'b' es una referencia al mismo objeto que 'a'
print(a is not c)  # True, porque 'c' es una copia de 'a', no el mismo objeto
```



``` python
a = [1, 2, 3]
b = 2

print('----------------------------------')
print('Operaciones de pertenencia:')
print('----------------------------------')
print('b in a:', b in a) # se usa (in)
print('b not in a:', b not in a) # se usa (not in)
print('----------------------------------')
```

# **Qué son las operaciones de pertenencia**

Las operaciones de pertenencia son aquellas que nos permiten verificar
si un elemento pertenece a una secuencia (como una lista, tupla o cadena
de texto). Se utilizan los operadores `in` y `not in` para comprobar la
pertenencia de un elemento a una secuencia.



## **Operador (`in`)**

El operador `in` se utiliza para verificar si un elemento está presente
en una secuencia. Devuelve `True` si el elemento se encuentra en la
secuencia y `False` en caso contrario. Por ejemplo, si tenemos una lista
de números y queremos comprobar si un número específico está en esa
lista, podemos usar el operador `in` para hacerlo.

``` python
numeros = [1, 2, 3, 4, 5]
numero_a_buscar = 3

if numero_a_buscar in numeros:
    print(f"{numero_a_buscar} está en la lista.")
else:
    print(f"{numero_a_buscar} no está en la lista.")
```

En este ejemplo, el operador `in` verifica si el número `3` está
presente en la lista `numeros`. Si lo está, se imprime un mensaje
indicando que está en la lista; de lo contrario, se indica que no está
presente.



## **Operador (`not in`)**

El operador `not in` se utiliza para verificar si un elemento no está
presente en una secuencia. Devuelve `True` si el elemento no se
encuentra en la secuencia y `False` en caso contrario. Por ejemplo, si
queremos comprobar si un número específico no está en una lista, podemos
usar el operador `not in` para hacerlo.

``` python

numeros = [1, 2, 3, 4, 5]
numero_a_buscar = 6

if numero_a_buscar not in numeros:
    print(f"{numero_a_buscar} no está en la lista.")
else:
    print(f"{numero_a_buscar} está en la lista.")
```

En este ejemplo, el operador `not in` verifica si el número `6` no está
presente en la lista `numeros`. Si no lo está, se imprime un mensaje
indicando que no está en la lista; de lo contrario, se indica que está
presente.



# **Operaciones de bits**

``` python
a = 10 # 1010
b = 3 # 0011
print('----------------------------------')
print('Operaciones de bits:')
print('----------------------------------')
print('a & b:', a & b) # se usa (&)
print('a | b:', a | b) # se usa (|)
print('a ^ b:', a ^ b) # se usa (^)
print('~a:', ~a) # se usa (~)
print('a << 1:', a << 1) # se usa (<<)
print('a >> 1:', a >> 1) # se usa (>>)
print('----------------------------------')
```

# **Qué son las operaciones de bits?**

Las operaciones de bits son operaciones que se realizan a nivel de bits
en los números binarios. Por ejemplo, la operación AND (&) compara cada
bit de dos números y devuelve un nuevo número que tiene un bit en 1 solo
si ambos bits de entrada son 1. La operación OR (\|) devuelve un nuevo
número que tiene un bit en 1 si al menos uno de los bits de entrada
es 1. La operación XOR (^) devuelve un nuevo número que tiene un bit en
1 si los bits de entrada son diferentes. La operación NOT (~) invierte
todos los bits del número. Las operaciones de desplazamiento (\<\< y
\>\>) desplazan los bits a la izquierda o a la derecha, respectivamente.



## **Operador (`&`)**

El operador `&` es el operador de "AND" a nivel de bits. Compara cada
bit de dos números y devuelve un nuevo número que tiene un bit en 1 solo
si ambos bits de entrada son 1. Por ejemplo, si tenemos los números 10
(1010 en binario) y 3 (0011 en binario), la operación `10 & 3` devuelve
2 (0010 en binario), ya que solo el segundo bit es 1 en ambos números.

### **Ejemplo:**

``` python

a = 10 # 1010
b = 3 # 0011

resultado = a & b # 0010
print(resultado) # 2
```



## **Operador (`|`)**

El operador `|` es el operador de "OR" a nivel de bits. Compara cada bit
de dos números y devuelve un nuevo número que tiene un bit en 1 si al
menos uno de los bits de entrada es 1. Por ejemplo, si tenemos los
números 10 (1010 en binario) y 3 (0011 en binario), la operación
`10 | 3` devuelve 11 (1011 en binario), ya que el primer, segundo y
cuarto bit son 1 en al menos uno de los números.

### **Ejemplo:**

``` python

a = 10 # 1010
b = 3 # 0011

resultado = a | b # 1011
print(resultado) # 11
```



## **Operador (`^`)**

El operador `^` es el operador de "XOR" a nivel de bits. Compara cada
bit de dos números y devuelve un nuevo número que tiene un bit en 1 si
los bits de entrada son diferentes. Por ejemplo, si tenemos los números
10 (1010 en binario) y 3 (0011 en binario), la operación `10 ^ 3`
devuelve 9 (1001 en binario), ya que el primer y tercer bit son
diferentes en los números.

### **Ejemplo:**

``` python

a = 10 # 1010
b = 3 # 0011

resultado = a ^ b # 1001
print(resultado) # 9
```



## **Operador (`~`)**

El operador `~` es el operador de "NOT" a nivel de bits. Invierte todos
los bits del número. Por ejemplo, si tenemos el número 10 (1010 en
binario), la operación `~10` devuelve -11
(11111111111111111111111111110101 en binario), ya que todos los bits se
invierten.

### **Ejemplo:**

``` python

a = 10 # 1010
resultado = ~a # 11111111111111111111111111110101
print(resultado) # -11
```



## **Operador (`<<`)**

El operador `<<` es el operador de desplazamiento a la izquierda.
Desplaza los bits del número a la izquierda un número específico de
posiciones. Por ejemplo, si tenemos el número 10 (1010 en binario) y lo
desplazamos a la izquierda una posición, obtenemos 20 (10100 en
binario), ya que se agrega un 0 al final del número.

### **Ejemplo:**

``` python

a = 10 # 1010
resultado = a << 1 # 10100
print(resultado) # 20
```



## **Operador (`>>`)**

El operador `>>` es el operador de desplazamiento a la derecha. Desplaza
los bits del número a la derecha un número específico de posiciones. Por
ejemplo, si tenemos el número 10 (1010 en binario) y lo desplazamos a la
derecha una posición, obtenemos 5 (0101 en binario), ya que se elimina
el último bit del número.

### **Ejemplo:**

``` python

a = 10 # 1010
resultado = a >> 1 # 0101
print(resultado) # 5
```

# **Ejemplo completo:**

``` python
a = 10 # 1010
b = 3 # 0011
print('a & b:', a & b) # 0010
print('a | b:', a | b) # 1011
print('a ^ b:', a ^ b) # 1001
print('~a:', ~a) # 11111111111111111111111111110101
print('a << 1:', a << 1) # 10100
print('a >> 1:', a >> 1) # 0101
```
