# 📌 Funciones en Python

## 1. ¿Qué son las funciones?

Las funciones son bloques de código reutilizables que encapsulan una serie de instrucciones para realizar una tarea específica. Su uso permite modularizar programas, facilitando su mantenimiento, legibilidad y depuración.

---

## 2. ¿Por qué utilizar funciones?

* **Modularidad**: Permiten dividir el programa en componentes más pequeños y manejables.
* **Reutilización**: Se evita la repetición de código, lo que reduce errores.
* **Escalabilidad**: Facilitan la extensión y evolución del software.
* **Mantenimiento**: Resulta más sencillo localizar y corregir errores.

---

## 3. ¿Cómo se define una función en Python?

Se utiliza la palabra reservada `def`, seguida del nombre de la función, paréntesis (que pueden incluir parámetros) y dos puntos. El cuerpo de la función debe ir indentado.

```python
def nombre_funcion(parametro1, parametro2):
    # Bloque de código
    return resultado
```

---

## 4. Ejemplo básico

```python
def suma(a, b):
    return a + b

resultado = suma(5, 3)
print(resultado)  # Salida: 8
```

---

## 5. Parámetros y argumentos

* **Parámetros**: Variables definidas en la declaración de la función.
* **Argumentos**: Valores reales pasados a la función cuando se invoca.

---

## 6. Parámetros con valores por defecto

Python permite asignar valores predeterminados a los parámetros, lo que los convierte en opcionales.

```python
def saludar(nombre, saludo="Hola"):
    print(f"{saludo}, {nombre}!")
```

**Ejemplos**:

```python
saludar("Ana")                     # Hola, Ana!
saludar("Ana", "Buenos días")     # Buenos días, Ana!
```

---

## 7. Número variable de argumentos

Mediante `*args` (argumentos posicionales) y `**kwargs` (argumentos con nombre), se pueden recibir múltiples valores.

```python
def sumar_todos(*args):
    return sum(args)

print(sumar_todos(1, 2, 3))  # Salida: 6
```

```python
def mostrar_info(**kwargs):
    for clave, valor in kwargs.items():
        print(f"{clave}: {valor}")

mostrar_info(nombre="Luis", edad=25)
```

---

## 8. Funciones lambda

Son funciones anónimas, definidas en una sola línea. Su uso se recomienda para operaciones simples o como argumentos en funciones de orden superior.

```python
suma = lambda x, y: x + y
print(suma(4, 6))  # Salida: 10
```

---

## 9. Funciones recursivas

Una función recursiva se llama a sí misma para resolver un problema en términos más pequeños. Es crucial definir una condición de parada.

```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n - 1)

print(factorial(5))  # Salida: 120
```

---

## 10. Funciones anidadas

Es posible definir funciones dentro de otras. Estas funciones internas tienen acceso al entorno local de la función externa.

```python
def exterior():
    def interior():
        print("Función interior")
    interior()

exterior()
```

---

## 11. Ámbito de las variables (Scope)

* **Local**: Dentro de la función.
* **Global**: Fuera de todas las funciones.
* **Nonlocal**: Dentro de funciones anidadas para modificar variables del entorno inmediato superior.

---

## 12. Documentación de funciones

Python permite documentar funciones mediante *docstrings*, lo cual facilita la comprensión del código por parte de otros desarrolladores.

```python
def sumar(a, b):
    """Devuelve la suma de dos números."""
    return a + b
```

Se puede acceder con `help(sumar)` o `sumar.__doc__`.

---