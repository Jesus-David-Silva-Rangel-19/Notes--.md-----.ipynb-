# 1. Python: Variables y Tipos de Datos

# 2. Variables

Las variables son contenedores que almacenan datos. En Python, no es necesario declarar el tipo de dato de una variable antes de asignarle un valor.

**Ejemplo de declaración de variables:**

```python
nombre = "Juan"  # Cadena de texto (str)
edad = 30        # Entero (int)
altura = 1.75    # Decimal (float)
es_estudiante = True  # Booleano (bool)
```

# 3. Tipos de Datos

Se describen a continuación los tipos de datos más comunes en Python, acompañados de ejemplos y aplicaciones.

## 3.1. Números enteros (`int`)

Valores numéricos sin decimales.

```python
a = 10
```

## 3.2. Números decimales (`float`)

Valores numéricos con parte fraccionaria.

```python
b = 3.14
```

## 3.3. Cadenas de texto (`str`)

Secuencias de caracteres que representan texto.

```python
c = "Hola, mundo"
```

## 3.4. Booleanos (`bool`)

Valores lógicos: `True` o `False`.

```python
d = True
```

## 3.5. Listas (`list`)

Colecciones ordenadas y mutables de elementos.

```python
e = [1, 2, 3, "Hola", True]
```

## 3.6. Diccionarios (`dict`)

Colecciones no ordenadas de pares clave-valor.

```python
f = {"nombre": "Juan", "edad": 30}
```

## 3.7. Tuplas (`tuple`)

Colecciones ordenadas e inmutables.

```python
g = (1, 2, 3)
```

## 3.8. Conjuntos (`set`)

Colecciones no ordenadas de elementos únicos.

```python
h = {1, 2, 3, 4, 5}
```

# 4. Tabla resumen de tipos de datos

| Tipo de dato | Descripción                  | Ejemplo              |
| ------------ | ---------------------------- | -------------------- |
| `int`        | Números enteros              | `42`                 |
| `float`      | Números decimales            | `3.14`               |
| `str`        | Texto                        | `"Hola, mundo"`      |
| `bool`       | Valores lógicos              | `True`, `False`      |
| `list`       | Listas mutables              | `[1, 2, 3]`          |
| `dict`       | Diccionarios (clave-valor)   | `{"clave": "valor"}` |
| `tuple`      | Tuplas inmutables            | `(1, 2, 3)`          |
| `set`        | Conjuntos (elementos únicos) | `{1, 2, 3}`          |

# 5. Ejemplos prácticos completos

```python
a = 10            # int
b = 3.14          # float
c = "Hola"        # str
d = True          # bool
e = [1, 2, 3]     # list
f = {"nombre":"Juan", "edad":30}  # dict
g = (1, 2, 3)     # tuple
h = {1, 2, 3}     # set

print(type(a), type(b), type(c), type(d), type(e), type(f), type(g), type(h))
```

# 6. Resumen

Los tipos de datos en Python permiten almacenar y manipular distintos tipos de información según la necesidad del programa. La flexibilidad de Python para manejar estos tipos sin declaración explícita facilita el desarrollo eficiente y claro. El dominio de estos conceptos es fundamental para la programación básica y el análisis de datos.

# 7. Preguntas de repaso

1. ¿Qué es una variable y para qué se utiliza en Python?
2. ¿Cuáles son los principales tipos de datos en Python?
3. ¿Cuál es la diferencia entre una lista y una tupla?
4. ¿Qué tipo de dato utilizaría para almacenar una colección de pares clave-valor?
5. ¿Qué representa un valor booleano y cómo se usa?
6. ¿Para qué sirve un conjunto (`set`) y qué característica principal tiene?
7. Proporcione un ejemplo simple de cada tipo de dato explicado.

---