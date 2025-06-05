# 1. **¿Qué son los condicionales?**

Los condicionales son estructuras de control que permiten ejecutar un
bloque de código si se cumple una condición determinada.

En Python, los condicionales más comunes son:

- `if`: Se utiliza para evaluar una condición y ejecutar un bloque de
  código si la condición es verdadera.

- `elif`: Se utiliza para evaluar una segunda condición si la primera
  condición es falsa.

- `else`: Se utiliza para ejecutar un bloque de código si todas las
  condiciones anteriores son falsas.

- `if` y `else` pueden ser anidados para evaluar múltiples condiciones.

------------------------------------------------------------------------

## 1.1. **Sintaxis de los condicionales**

``` python
if condicion1:
    # Bloque de código si condicion1 es verdadera
elif condicion2:
    # Bloque de código si condicion2 es verdadera
else:
    # Bloque de código si ninguna de las condiciones anteriores es verdadera
```

------------------------------------------------------------------------

# 2. **¿Qué hace la estructura de control `if`?**

La estructura de control `if` permite ejecutar un bloque de código si se
cumple una condición.

La sintaxis básica es la siguiente:

``` python
if condicion:
    # bloque de código a ejecutar si la condición es verdadera
```

# 3. **Ejemplo de uso de la estructura de control if**

``` python
edad = 18
if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")
# Salida:
# Eres mayor de edad
```

------------------------------------------------------------------------

# 4. **¿Qué hace la estructura de control `if` con `elif`?**

La estructura de control `if` con `elif` permite evaluar múltiples
condiciones en una sola declaración. Si la primera condición no se
cumple, se evalúa la siguiente condición `elif`, y así sucesivamente.

Si ninguna de las condiciones se cumple, se puede usar un bloque `else`
para manejar el caso por defecto.

## 4.1. La sintaxis básica es la siguiente:

``` python
if condicion1:
    # bloque de código a ejecutar si condicion1 es verdadera
elif condicion2:
    # bloque de código a ejecutar si condicion2 es verdadera
else:
    # bloque de código a ejecutar si ninguna de las condiciones anteriores es verdadera
```

## 4.2. **Ejemplo de uso de la estructura de control if con elif**

``` python
edad = 18
if edad < 13:
    print("Eres un niño")
elif edad < 18:
    print("Eres un adolescente")
else:
    print("Eres un adulto")

# Salida: Eres un adulto
```

------------------------------------------------------------------------

# 5. **¿Qué hace la estructura de control `if` con `else`?**

La estructura de control `if` con `else` permite ejecutar un bloque de
código si la condición no se cumple. Es útil para manejar el caso por
defecto cuando ninguna de las condiciones anteriores es verdadera.

# 6. **La sintaxis básica es la siguiente:**

``` python
if condicion:
    # bloque de código a ejecutar si la condición es verdadera
else:
    # bloque de código a ejecutar si la condición es falsa
```

# 7. **Ejemplo de uso de la estructura de control if con else**

``` python
edad = 18
if edad >= 18:
    print("Eres mayor de edad")
else:
    print("Eres menor de edad")

# Salida: Eres mayor de edad
```

------------------------------------------------------------------------

# 8. **¿Qué hace la estructura de control `if` con `elif` y `else`?**

La estructura de control `if` con `elif` y `else` permite evaluar
múltiples condiciones y manejar el caso por defecto en una sola
declaración. Es útil para simplificar el código y hacerlo más legible.

# 9. **La sintaxis básica es la siguiente:**

``` python

if condicion1:
    # bloque de código a ejecutar si condicion1 es verdadera
elif condicion2:
    # bloque de código a ejecutar si condicion2 es verdadera
else:
    # bloque de código a ejecutar si ninguna de las condiciones anteriores es verdadera
```

# 10. **Ejemplo de uso de con `if`, `elif`, `else`**

``` python
edad = 18
if edad < 13:
    print("Eres un niño")
elif edad < 18:
    print("Eres un adolescente")
else:
    print("Eres un adulto")

# Salida: Eres un adulto
```