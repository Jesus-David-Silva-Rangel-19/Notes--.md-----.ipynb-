
# **Tipos de datos**

 | Tipo de dato |  Nombre         |     Ejemplo            |
 | -------------- | ------------- | ---------------------- |
| `str`         | Texto         |   `"Hola, mundo"`        |
|  `int`         | Entero       |   `42`                   |
|  `float`      | Decimal       |   `3.14`                 |
|  `bool`        | Booleano     |   `True`, `False`        |
|  `list`       | Lista         |   `[1, 2, 3]`            |
|  `dict`       | Diccionario   |   `{"clave": "valor"}`   |
|  `tuple`      | Tupla         |   `(1, 2, 3)`            |
|  `set`        | Conjunto      |   `{1, 2, 3}`            |


``` python
# Números enteros (int)
a = 10
print("Entero:", a, type(a))

# Números decimales (float)
b = 3.14
print("Decimal:", b, type(b))

# Cadenas de texto (str)
c = "Hola, mundo"
print("Cadena:", c, type(c))

# Booleanos (bool)
d = True
print("Booleano:", d, type(d))

# Listas (list)
e = [1, 2, 3, 4, 5]
print("Lista:", e, type(e))

# Diccionarios (dict)
f = {"nombre": "Juan", "edad": 30}
print("Diccionario:", f, type(f))

# Tuplas (tuple)
g = (1, 2, 3)
print("Tupla:", g, type(g))

# Conjuntos (set)
h = {1, 2, 3, 4, 5}
print("Conjunto:", h, type(h))
```

# **¿Que representa cada tipo de dato?**

## `int`
Son números enteros, como *1, 2, 3*.
## `float`
Son números decimales, como *3.14, 2.5*.
## `str`
Son cadenas de texto, como *"Hola, mundo"*.
## `bool`
Son valores booleanos, como *True* o *False*.
## `list`
Son listas, que pueden contener múltiples elementos, como *[1, 2, 3]*.
## `dict`
Son diccionarios, que almacenan pares clave-valor, como *{"nombre": "Juan", "edad": 30}*.
## `tuple`
Son tuplas, que son similares a las listas pero inmutables, como *(1, 2, 3)*.
## `set`
Son conjuntos, que almacenan elementos únicos, como *{1, 2, 3}*.


## **¿Que son los datos booleanos?**

Los datos booleanos son un tipo de dato que puede tener solo dos valores: 
*True* (verdadero) o *False* (falso). 

Los booleanos son útiles para representar condiciones lógicas y tomar decisiones en el código. 

Por ejemplo, se pueden usar en estructuras de control como *if*, *while* y *for*
para determinar el flujo de ejecución del programa.

### **Ejemplo de uso de booleanos**

```python
es_mayor_de_edad = True
if es_mayor_de_edad:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")    
```

# **¿Que son las listas?**

Las listas son estructuras de datos que permiten almacenar múltiples elementos en una sola variable.

Pueden contener elementos de diferentes tipos, como números, cadenas de texto, booleanos, etc.

Las listas son mutables, lo que significa que puedes modificar su contenido después de haberlas creado.

### **Ejemplo de lista**
``` python
mi_lista = [1, 2, 3, "Hola", True]
print("Lista:", mi_lista)
```

# **¿Qué son los diccionarios?**

Los diccionarios son estructuras de datos que almacenan pares clave-valor. Se utilizan para almacenar información de manera organizada y accesible.

### **Por ejemplo**

un diccionario que almacena información de una persona:

``` python
persona = {
    "nombre": "Juan",
    "edad": 30,
    "ciudad": "Madrid"
}
```

# **¿Qué son las tuplas?**

Las tuplas son estructuras de datos inmutables que pueden contener
múltiples elementos. Se definen con paréntesis y son útiles para
almacenar datos que no deben cambiar.

### **Ejemplo de tupla**

```python
tupla = (1, 2, 3)
print("Tupla:", tupla, type(tupla))
```


# **¿Qué son los conjuntos (set)?**

Los conjuntos son una colección desordenada de elementos únicos. 

No permiten duplicados y no tienen un orden específico. Se utilizan para realizar operaciones matemáticas como la unión, intersección y diferencia entre conjuntos.

### **Ejemplo de conjunto**

```python
conjunto = {1, 2, 3, 4, 5}
print("Conjunto:", conjunto, type(conjunto))
```
