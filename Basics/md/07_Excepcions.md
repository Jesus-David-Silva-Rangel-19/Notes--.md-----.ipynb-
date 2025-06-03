# 🐍 **Excepciones en Python**

## 📌 **¿Qué es una excepción?**

Una **excepción** en Python es un **evento inesperado** que ocurre durante la ejecución de un programa y que interrumpe su flujo normal.
Las excepciones surgen comúnmente debido a errores como:

- División entre cero
- Acceso a archivos inexistentes
- Conversión inválida de tipos
- Índices fuera de rango

------------------------------------------------------------------------

## 🎯 **¿Para qué se usa?**

Las excepciones se utilizan para:

- **Controlar errores** sin detener abruptamente la ejecución del
  programa.
- **Detectar y gestionar fallos** de manera controlada.
- **Proteger el flujo del programa**, aplicando medidas correctivas o
  alternativas cuando ocurre un error.

------------------------------------------------------------------------

## 🧱 **Estructura de manejo de excepciones en Python**

``` python
try:
    # Bloque de código que puede generar una excepción
    ...
except NombreDeLaExcepcion:
    # Bloque de código que se ejecuta si ocurre esa excepción
    ...
else:
    # (Opcional) Se ejecuta si no se produce ninguna excepción
    ...
finally:
    # (Opcional) Siempre se ejecuta, ocurra o no una excepción
    ...
```

### 🔹 **Componentes**

- `try`: Contiene el código que puede generar un error.
- `except`: Captura y maneja el error específico.
- `else`: Se ejecuta solo si no se genera ninguna excepción.
- `finally`: Se ejecuta siempre, útil para liberar recursos (archivos,
  conexiones, etc.).

------------------------------------------------------------------------

## 🧪 **Ejemplos prácticos**

### **Ejemplo 1: División entre cero**

``` python
try:
    resultado = 10 / 0
except ZeroDivisionError:
    print("Error: No se puede dividir entre cero.")
```

### **Ejemplo 2: Manejo de múltiples excepciones**

``` python
try:
    numero = int(input("Ingrese un número: "))
    resultado = 10 / numero
except ValueError:
    print("Error: Debe ingresar un número válido.")
except ZeroDivisionError:
    print("Error: División entre cero no permitida.")
```

### **Ejemplo 3: Uso de `else` y `finally`**

``` python
try:
    archivo = open("datos.txt", "r")
    contenido = archivo.read()
except FileNotFoundError:
    print("Error: El archivo no existe.")
else:
    print("Lectura exitosa:")
    print(contenido)
finally:
    print("Proceso finalizado.")
```

------------------------------------------------------------------------

## 📘 **Buenas prácticas**

- Capturar solo las excepciones que se esperan manejar.
- No usar `except:` sin especificar la excepción (excepto para fines de
  depuración).
- Utilizar `finally` para cerrar archivos o liberar recursos.
- Crear excepciones personalizadas cuando se requiera un control más
  detallado.

------------------------------------------------------------------------

## 🧩 **Excepciones personalizadas**

``` python
class MiExcepcion(Exception):
    pass

try:
    raise MiExcepcion("Ocurrió un error personalizado.")
except MiExcepcion as e:
    print(f"Error personalizado: {e}")
```

------------------------------------------------------------------------

## 📚 **Referencias**

- [Documentación oficial de Python –
  Excepciones](https://docs.python.org/3/tutorial/errors.html)

------------------------------------------------------------------------