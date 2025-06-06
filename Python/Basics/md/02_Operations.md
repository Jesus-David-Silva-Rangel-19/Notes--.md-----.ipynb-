# 📘 Python: Fundamentos de Operaciones Básicas

Esta guía documenta de forma estructurada y precisa los operadores fundamentales del lenguaje de programación Python, esenciales para el desarrollo de scripts, algoritmos y lógica computacional básica.

---

## 🧮 1. Operadores Aritméticos

Permiten realizar cálculos matemáticos entre operandos. Son ampliamente utilizados en cálculos, funciones, estructuras de control y lógica algorítmica.

### 1.1. Tabla de operadores aritméticos

| Operador | Descripción        | Ejemplo  | Resultado |
| -------- | ------------------ | -------- | --------- |
| `+`      | Suma               | `7 + 3`  | `10`      |
| `-`      | Resta              | `7 - 3`  | `4`       |
| `*`      | Multiplicación     | `7 * 3`  | `21`      |
| `/`      | División (decimal) | `7 / 3`  | `2.333`   |
| `**`     | Potenciación       | `2 ** 3` | `8`       |
| `//`     | División entera    | `7 // 3` | `2`       |
| `%`      | Módulo (residuo)   | `7 % 3`  | `1`       |

### 1.2. Ejemplo de implementación

```python
a = 7
b = 3

print("Suma:", a + b)
print("Resta:", a - b)
print("Multiplicación:", a * b)
print("División:", a / b)
print("Potencia:", a ** b)
print("División entera:", a // b)
print("Módulo:", a % b)
```

---

## 🔁 2. Operadores de Asignación

Permiten asignar valores a variables. También se utilizan para actualizar el valor de una variable aplicando una operación sobre sí misma.

### 2.1. Tabla de operadores de asignación

| Operador | Significado                  | Ejemplo   | Equivalente  |
| -------- | ---------------------------- | --------- | ------------ |
| `=`      | Asignación simple            | `a = 5`   | —            |
| `+=`     | Suma y asignación            | `a += 3`  | `a = a + 3`  |
| `-=`     | Resta y asignación           | `a -= 2`  | `a = a - 2`  |
| `*=`     | Multiplicación y asignación  | `a *= 4`  | `a = a * 4`  |
| `/=`     | División y asignación        | `a /= 2`  | `a = a / 2`  |
| `**=`    | Potencia y asignación        | `a **= 2` | `a = a ** 2` |
| `//=`    | División entera y asignación | `a //= 3` | `a = a // 3` |
| `%=`     | Módulo y asignación          | `a %= 3`  | `a = a % 3`  |

### 2.2. Ejemplo de uso

```python
a = 10

a += 5   # a = a + 5 → 15
a -= 2   # a = a - 2 → 13
a *= 3   # a = a * 3 → 39
a /= 3   # a = a / 3 → 13.0
a **= 2  # a = a ** 2 → 169.0
a //= 4  # a = a // 4 → 42.0
a %= 5   # a = a % 5 → 2.0

print("Resultado final:", a)
```

> 📌 *Los operadores de asignación permiten escribir código más compacto y legible, y son fundamentales en estructuras iterativas y acumulativas.*

---

## 🔎 3. Operadores de Comparación

Evalúan relaciones entre dos valores. Retornan un valor booleano (`True` o `False`) y son claves en estructuras condicionales (`if`, `while`, etc.).

### 3.1. Tabla de operadores de comparación

| Operador | Descripción       | Ejemplo  | Resultado |
| -------- | ----------------- | -------- | --------- |
| `==`     | Igual a           | `5 == 5` | `True`    |
| `!=`     | Distinto de       | `5 != 3` | `True`    |
| `>`      | Mayor que         | `5 > 3`  | `True`    |
| `<`      | Menor que         | `5 < 3`  | `False`   |
| `>=`     | Mayor o igual que | `5 >= 5` | `True`    |
| `<=`     | Menor o igual que | `5 <= 3` | `False`   |

### 3.2. Ejemplo de aplicación

```python
x = 5
y = 3

print("¿x > y?:", x > y)
print("¿x < y?:", x < y)
print("¿x == y?:", x == y)
print("¿x != y?:", x != y)
print("¿x >= y?:", x >= y)
print("¿x <= y?:", x <= y)
```

---

## ⚙️ 4. Operadores Lógicos

Se utilizan para combinar expresiones condicionales. El resultado siempre es un valor booleano.

### 4.1. Tabla de operadores lógicos

| Operador | Descripción                               | Ejemplo             | Resultado |
| -------- | ----------------------------------------- | ------------------- | --------- |
| `and`    | Verdadero si **ambas** condiciones lo son | `(x > 0 and y > 0)` | `True`    |
| `or`     | Verdadero si **una o ambas** lo son       | `(x > 0 or y < 0)`  | `True`    |
| `not`    | Invierte el valor de la condición         | `not(x > 0)`        | `False`   |

### 4.2. Ejemplo práctico

```python
x = 4
y = -2

print("AND lógico:", x > 0 and y > 0)
print("OR lógico:", x > 0 or y < 0)
print("NOT lógico:", not x > 0)
```

---