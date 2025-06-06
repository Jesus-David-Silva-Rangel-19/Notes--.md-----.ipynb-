
# Python: Variables y Tipos de Datos

## 1. Introducción

Python es un lenguaje de programación de tipado dinámico, lo que significa que no es necesario declarar el tipo de dato al crear una variable. 
Las variables son espacios de memoria donde se almacena información que puede ser utilizada y modificada durante la ejecución de un programa.

---

## 2. Declaración de Variables

Una variable se define asignando un valor con el operador `=`. No se requiere una declaración previa de su tipo.

### 📌 Ejemplo:

```python
nombre = "Juan"          # Cadena de texto (str)
edad = 30                # Número entero (int)
altura = 1.75            # Número decimal (float)
es_estudiante = True     # Valor booleano (bool)
```

> ✅ **Nota:** Las variables son esenciales para escribir programas dinámicos y reutilizables.

---

## 3. Tipos de Datos en Python

Python ofrece varios tipos de datos integrados. A continuación, se describen los más comunes:

### 3.1. Enteros (`int`)

Números sin parte decimal. Pueden ser positivos, negativos o cero.

```python
numero = 10
print(numero, type(numero))
```

> 🔎 **Uso:** Contadores, edades, índices.

---

### 3.2. Decimales (`float`)

Números reales con parte fraccionaria.

```python
pi = 3.14159
print(pi, type(pi))
```

> 🔎 **Uso:** Mediciones, cálculos precisos.

---

### 3.3. Cadenas de texto (`str`)

Secuencias de caracteres, delimitadas por comillas simples o dobles.

```python
mensaje = "Hola, Python"
print(mensaje, type(mensaje))
```

> 🔎 **Uso:** Nombres, mensajes, archivos de texto.

---

### 3.4. Booleanos (`bool`)

Solo puede tomar dos valores: `True` o `False`.

```python
activo = True
print(activo, type(activo))
```

> 🔎 **Uso:** Condiciones lógicas y estructuras de control.

---

### 3.5. Listas (`list`)

Colecciones ordenadas y mutables. Permiten duplicados y elementos de distinto tipo.

```python
mi_lista = [1, "Hola", True]
print(mi_lista, type(mi_lista))
```

> 🔎 **Uso:** Conjuntos de elementos relacionados.

---

### 3.6. Diccionarios (`dict`)

Estructuras de pares clave-valor. No ordenadas (desde Python 3.7 en adelante sí preservan orden de inserción).

```python
persona = {"nombre": "Juan", "edad": 30}
print(persona, type(persona))
```

> 🔎 **Uso:** Representación de objetos o registros.

---

### 3.7. Tuplas (`tuple`)

Colecciones ordenadas e inmutables.

```python
coordenadas = (10.5, 20.3)
print(coordenadas, type(coordenadas))
```

> 🔎 **Uso:** Datos fijos como coordenadas o configuraciones.

---

### 3.8. Conjuntos (`set`)

Colecciones no ordenadas de elementos únicos.

```python
valores = {1, 2, 3, 3}
print(valores, type(valores))
```

> 🔎 **Uso:** Operaciones matemáticas con conjuntos, eliminación de duplicados.

---

## 4. Tabla Resumen de Tipos de Datos

| Tipo    | Nombre      | Ejemplo              |
| ------- | ----------- | -------------------- |
| `str`   | Cadena      | `"Hola"`             |
| `int`   | Entero      | `42`                 |
| `float` | Decimal     | `3.14`               |
| `bool`  | Booleano    | `True`, `False`      |
| `list`  | Lista       | `[1, 2, 3]`          |
| `dict`  | Diccionario | `{"nombre": "Juan"}` |
| `tuple` | Tupla       | `(1, 2)`             |
| `set`   | Conjunto    | `{1, 2, 3}`          |

---

## 5. Ejemplos de Uso por Tipo de Dato

### 5.1. Entero (`int`)

```python
numero_entero = 42
print("Entero:", numero_entero, type(numero_entero))
```

---

### 5.2. Decimal (`float`)

```python
numero_decimal = 3.14
print("Decimal:", numero_decimal, type(numero_decimal))
```

---

### 5.3. Cadena (`str`)

```python
texto = "Hola, mundo"
print("Cadena:", texto, type(texto))
```

---

### 5.4. Booleano (`bool`)

```python
es_adulto = True
if es_adulto:
    print("Es mayor de edad")
```

---

### 5.5. Lista (`list`)

```python
colores = ["rojo", "verde", "azul"]
print("Lista:", colores, type(colores))
```

---

### 5.6. Diccionario (`dict`)

```python
alumno = {"nombre": "Ana", "edad": 22}
print("Diccionario:", alumno, type(alumno))
```

---

### 5.7. Tupla (`tuple`)

```python
fecha = (2025, 6, 6)
print("Tupla:", fecha, type(fecha))
```

---

### 5.8. Conjunto (`set`)

```python
numeros_unicos = {1, 2, 3, 2, 1}
print("Conjunto:", numeros_unicos, type(numeros_unicos))
```

---

## 6. Conclusión

Los tipos de datos son fundamentales en la programación con Python, ya que definen cómo se almacena, manipula y procesa la información. 
Comprender sus diferencias y aplicaciones permite escribir código más claro, eficiente y estructurado.

> 🎓 **Sugerencia del profesor:** Explora funciones como `type()`, `len()` y `isinstance()` para profundizar en el manejo de tipos de datos.

---
