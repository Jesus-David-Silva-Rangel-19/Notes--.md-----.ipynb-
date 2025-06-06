# 🧾 Python: Indexación y Segmentación de Datos

En Python, las operaciones de **indexación** y **segmentación (slicing)** permiten acceder y manipular elementos dentro de estructuras de datos como listas, cadenas, tuplas y otros objetos secuenciales.

---

## 🔢 1. Indexación

### 1.1. ¿Qué es?

La **indexación** permite acceder a elementos individuales en estructuras ordenadas.
Python utiliza un sistema de **índices basados en cero (0-based indexing)**, lo que significa que el primer elemento tiene índice `0`, el segundo `1`, y así sucesivamente.

### 1.2. Sintaxis general

```python
estructura[indice]
```

* `estructura`: lista, cadena o tupla.
* `indice`: número entero que indica la posición.

### 1.3. Ejemplo básico

```python
mi_lista = [10, 20, 30, 40, 50]

print("Primer elemento:", mi_lista[0])
print("Segundo elemento:", mi_lista[1])
```

📤 **Salida:**

```
Primer elemento: 10
Segundo elemento: 20
```

### 1.4. Índices negativos

En Python también pueden usarse índices negativos para acceder a elementos desde el final de la estructura.

```python
print("Último elemento:", mi_lista[-1])
print("Penúltimo elemento:", mi_lista[-2])
```

📤 **Salida:**

```
Último elemento: 50
Penúltimo elemento: 40
```

### 1.5. Error por índice fuera de rango

Acceder a un índice inexistente genera un error `IndexError`.

```python
mi_lista = [10, 20, 30]
print(mi_lista[5])
```

📤 **Error:**

```
IndexError: list index out of range
```

---

## ✂️ 2. Segmentación (Slicing)

### 2.1. ¿Qué es?

La **segmentación** permite extraer subestructuras (sublistas, subcadenas, etc.) mediante la especificación de un rango de índices.

### 2.2. Sintaxis general

```python
estructura[inicio:fin:paso]
```

* `inicio`: índice inicial (incluido).
* `fin`: índice final (excluido).
* `paso`: tamaño del salto entre elementos (opcional).

### 2.3. Ejemplo básico

```python
mi_lista = [10, 20, 30, 40, 50]

sub_lista = mi_lista[1:4]  # Del índice 1 al 3
print("Sublista:", sub_lista)
```

📤 **Salida:**

```
Sublista: [20, 30, 40]
```

### 2.4. Omisión de índices

Python permite omitir el índice de inicio o el de fin.

```python
# Desde el inicio hasta el índice 3 (sin incluir)
print(mi_lista[:3])  # [10, 20, 30]

# Desde el índice 2 hasta el final
print(mi_lista[2:])  # [30, 40, 50]
```

### 2.5. Segmentación con paso

Permite seleccionar elementos saltándose valores según un patrón definido.

```python
print(mi_lista[::2])  # Toma cada segundo elemento
```

📤 **Salida:**

```
[10, 30, 50]
```

### 2.6. Segmentación inversa

Para invertir una lista o cadena:

```python
print(mi_lista[::-1])  # Inversión total
```

📤 **Salida:**

```
[50, 40, 30, 20, 10]
```

---

## 🧠 Resumen General

| Acción                     | Sintaxis           | Ejemplo          | Resultado              |
| -------------------------- | ------------------ | ---------------- | ---------------------- |
| Acceder al primer elemento | `estructura[0]`    | `mi_lista[0]`    | `10`                   |
| Acceder al último elemento | `estructura[-1]`   | `mi_lista[-1]`   | `50`                   |
| Sublista del 1 al 3        | `estructura[1:4]`  | `mi_lista[1:4]`  | `[20, 30, 40]`         |
| Desde el inicio al 2       | `estructura[:3]`   | `mi_lista[:3]`   | `[10, 20, 30]`         |
| Desde el 2 al final        | `estructura[2:]`   | `mi_lista[2:]`   | `[30, 40, 50]`         |
| Segmento con saltos de 2   | `estructura[::2]`  | `mi_lista[::2]`  | `[10, 30, 50]`         |
| Estructura invertida       | `estructura[::-1]` | `mi_lista[::-1]` | `[50, 40, 30, 20, 10]` |

---
