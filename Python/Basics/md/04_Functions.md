# **¿Qué son las funciones?**

Las funciones son bloques de código que se pueden reutilizar. Se definen
una vez y se pueden llamar tantas veces como sea necesario.

# **¿Por qué usar funciones?**

Las funciones permiten organizar el código, hacerlo más legible y
reutilizable. Además, facilitan la depuración y el mantenimiento del
código. Las funciones también permiten dividir el código en partes más
pequeñas y manejables, lo que facilita su comprensión y modificación.
Las funciones pueden recibir parámetros y devolver valores, lo que las
hace muy versátiles.

# **¿Cómo se definen las funciones?**

Las funciones se definen con la palabra clave `def`, seguida del nombre
de la función y paréntesis. Dentro de los paréntesis se pueden
especificar los parámetros que la función recibirá. El bloque de código
que forma el cuerpo de la función debe estar indentado.

``` python

def nombre_funcion(parametro1, parametro2):
    # Código de la función
    return resultado
```

# **Ejemplo de función**

``` python

def suma(a, b):
    resultado = a + b
    return resultado
```

# **Llamando a la función**

``` python

resultado = suma(5, 3)
print(resultado)  # Salida: 8
```

# **Funciones con parámetros opcionales**

Las funciones pueden tener parámetros opcionales, que tienen un valor
por defecto. Si no se proporciona un valor para ese parámetro al llamar
a la función, se usará el valor por defecto.

``` python

def saludar(nombre, saludo="Hola"):
    print(f"{saludo}, {nombre}!")
```

# **Llamando a la función con y sin parámetro opcional**

``` python

saludar("Juan")  # Salida: Hola, Juan!
saludar("Juan", "Buenos días")  # Salida: Buenos días, Juan!
```

# **Funciones con número variable de argumentos**

Las funciones pueden aceptar un número variable de argumentos utilizando
el operador `*`. Esto permite pasar una lista de argumentos a la
función.

``` python

def sumar_todos(*args):
    suma = 0
    for num in args:
        suma += num
    return suma
```

# **Llamando a la función con número variable de argumentos**

``` python

resultado = sumar_todos(1, 2, 3, 4, 5)
print(resultado)  # Salida: 15
```

# **Funciones lambda**

Las funciones lambda son funciones anónimas que se definen en una sola
línea. Se utilizan para crear funciones pequeñas y rápidas sin necesidad
de definirlas con `def`.

``` python

suma = lambda a, b: a + b
resultado = suma(5, 3)
print(resultado)  # Salida: 8
```

# **Funciones recursivas**

Las funciones recursivas son aquellas que se llaman a sí mismas para
resolver un problema. Se utilizan para problemas que pueden dividirse en
subproblemas más pequeños.

``` python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
```

------------------------------------------------------------------------

# **Tipos de funciones**

## **Funciones sin retorno**

Son funciones que no devuelven ningún valor. Se utilizan para realizar
tareas específicas, como imprimir mensajes o modificar variables
globales.

``` python

def saludar():
    print("¡Hola, mundo!")
    saludar()

saludar()
```

## **Funciones con retorno**

Son funciones que devuelven un valor al finalizar su ejecución. Se
utilizan para realizar cálculos o procesar datos y devolver el
resultado.

``` python
def sumar(a, b):
    return a + b
resultado = sumar(5, 3)

print("El resultado de la suma es:", resultado)
```

## **Funciones con parámetros**

Son funciones que aceptan argumentos al ser llamadas. Estos argumentos
pueden ser utilizados dentro de la función para realizar operaciones o
cálculos.

``` python
def multiplicar(a, b):
    return a * b
resultado = multiplicar(4, 5)

print("El resultado de la multiplicación es:", resultado)
```

## **Funciones con parámetros opcionales**

Son funciones que permiten definir parámetros con valores
predeterminados. Si no se proporciona un valor al llamar a la función,
se utilizará el valor predeterminado.

``` python
def saludar(nombre="mundo"):
    print(f"¡Hola, {nombre}!")
saludar()
saludar("Juan")
```

## **Funciones anónimas (lambda)**

Son funciones que no tienen un nombre y se definen en una sola línea. Se
utilizan para operaciones simples y se pueden asignar a variables o
pasar como argumentos a otras funciones.

```python
suma = lambda a, b: a + b
resultado = suma(2, 3)
print("El resultado de la suma es:", resultado)
```

## **Funciones recursivas**

Son funciones que se llaman a sí mismas para resolver un problema. Se utilizan para problemas que pueden dividirse en subproblemas más pequeños, como el cálculo de factoriales o la serie de Fibonacci.

```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
resultado = factorial(5)
print("El factorial de 5 es:", resultado)
```

## **Funciones de orden superior**

Son funciones que pueden recibir otras funciones como argumentos o
devolver funciones como resultado. Se utilizan para crear funciones más
complejas y flexibles.

``` python
def aplicar_funcion(funcion, lista):
    return [funcion(x) for x in lista]

def cuadrado(x):
    return x ** 2

numeros = [1, 2, 3, 4, 5]
resultado = aplicar_funcion(cuadrado, numeros)
print("Los cuadrados de los números son:", resultado)
```

## **Funciones generadoras**

Son funciones que utilizan la palabra clave `yield` para devolver un
valor y pausar su ejecución. Se utilizan para crear iteradores y generar
secuencias de valores de manera eficiente.

``` python
def contar_hasta(n):
    for i in range(n):
        yield i
for numero in contar_hasta(5):
    print(numero)
```

## **Funciones decoradoras**

Son funciones que modifican el comportamiento de otras funciones. Se
utilizan para agregar funcionalidades adicionales, como la medición del
tiempo de ejecución o la verificación de permisos.

``` python
def decorador(funcion):
    def funcion_decorada():
        print("Antes de llamar a la función")
        funcion()
        print("Después de llamar a la función")
    return funcion_decorada
@decorador

def saludar():
    print("¡Hola, mundo!")
saludar()
```

## **Funciones de biblioteca estándar**

La biblioteca estándar de Python incluye muchas funciones útiles que se
pueden utilizar en programas. Algunas de las funciones más comunes son:

- `len()`: Devuelve la longitud de un objeto.
- `max()`: Devuelve el valor máximo de un iterable.
- `min()`: Devuelve el valor mínimo de un iterable.
- `sum()`: Devuelve la suma de los elementos de un iterable.
- `sorted()`: Devuelve una lista ordenada de los elementos de un
  iterable.
- `map()`: Aplica una función a cada elemento de un iterable y devuelve
  un nuevo iterable.
- `filter()`: Filtra los elementos de un iterable según una función y
  devuelve un nuevo iterable.
- `reduce()`: Aplica una función acumulativa a los elementos de un
  iterable y devuelve un solo valor.
- `zip()`: Combina varios iterables en un solo iterable de tuplas.
- `enumerate()`: Devuelve un iterable de tuplas que contienen el índice
  y el valor de cada elemento de un iterable.
- `any()`: Devuelve `True` si al menos un elemento de un iterable es
  verdadero.
- `all()`: Devuelve `True` si todos los elementos de un iterable son
  verdaderos.
- `map()`: Aplica una función a cada elemento de un iterable y devuelve
  un nuevo iterable

## **Funciones de manejo de excepciones**

Las funciones de manejo de excepciones se utilizan para gestionar
errores y excepciones en el código. Se utilizan las palabras clave
`try`, `except`, `else` y `finally` para definir bloques de código que
pueden generar excepciones y cómo manejarlas.

``` python
def dividir(a, b):
    try:
        resultado = a / b
    except ZeroDivisionError:
        print("Error: División por cero")
    else:
        print("El resultado de la división es:", resultado)
    finally:
        print("Fin de la función dividir")
}
dividir(10, 2)
dividir(10, 0)
```

## **Funciones de prueba**

Las funciones de prueba se utilizan para verificar el correcto
funcionamiento de otras funciones. Se pueden utilizar bibliotecas como
`unittest` o `pytest` para crear y ejecutar pruebas automatizadas.

``` python
import unittest
from mi_modulo import sumar
class TestFunciones(unittest.TestCase):
    def test_sumar(self):
        self.assertEqual(sumar(2, 3), 5)
        self.assertEqual(sumar(-1, 1), 0)
        self.assertEqual(sumar(0, 0), 0)
if __name__ == '__main__':
    unittest.main()
```

## **Funciones de documentación**

Las funciones de documentación se utilizan para proporcionar información
sobre el funcionamiento y uso de otras funciones. Se pueden utilizar
comentarios y cadenas de documentación (docstrings) para describir el
propósito, los parámetros y el valor de retorno de una función.

``` python
def sumar(a, b):
    """
    Suma dos números y devuelve el resultado.
    
    Parámetros:
    a (int): Primer número.
    b (int): Segundo número.
    
    Retorna:
    int: La suma de a y b.
    """
    return a + b
resultado = sumar(2, 3)
print("El resultado de la suma es:", resultado)
```

## **Funciones de depuración**

Las funciones de depuración se utilizan para identificar y corregir
errores en el código. Se pueden utilizar herramientas como `pdb` o
`logging` para realizar un seguimiento del flujo de ejecución y los
valores de las variables.

``` python
import pdb
def sumar(a, b):
    pdb.set_trace()  # Inicia el depurador
    return a + b
resultado = sumar(2, 3)

print("El resultado de la suma es:", resultado)
```

## **Funciones de optimización**

Las funciones de optimización se utilizan para mejorar el rendimiento y
la eficiencia del código. Se pueden utilizar técnicas como la
memoización, la paralelización o el uso de algoritmos más eficientes
para reducir el tiempo de ejecución y el consumo de recursos.

``` python
def fibonacci(n, memo={}):
    if n in memo:
        return memo[n]
    if n <= 1:
        return n
    memo[n] = fibonacci(n - 1, memo) + fibonacci(n - 2, memo)
    return memo[n]
resultado = fibonacci(10)
print("El décimo número de Fibonacci es:", resultado)
```

## **Funciones de programación funcional**

La programación funcional es un paradigma de programación que se basa en
el uso de funciones puras y evita el uso de estados mutables y efectos
secundarios. Se pueden utilizar funciones como `map()`, `filter()` y
`reduce()` para aplicar transformaciones y operaciones a colecciones de
datos sin modificar su estado original.

``` python
from functools import reduce
def sumar(a, b):
    return a + b
numeros = [1, 2, 3, 4, 5]
suma_total = reduce(sumar, numeros)
print("La suma total de los números es:", suma_total)
```

## **Funciones de programación orientada a objetos**

La programación orientada a objetos es un paradigma de programación que
se basa en el uso de clases y objetos. Las funciones se utilizan como
métodos dentro de las clases para definir el comportamiento y las
propiedades de los objetos.

``` python

class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def saludar(self):
        print(f"¡Hola, soy {self.nombre} y tengo {self.edad} años!")
persona1 = Persona("Juan", 30)
persona1.saludar()
```

## **Funciones de programación asíncrona**

La programación asíncrona se utiliza para realizar operaciones de
entrada/salida sin bloquear el flujo de ejecución del programa. Se
pueden utilizar funciones `async` y `await` para definir funciones
asíncronas y esperar a que se completen las operaciones.

``` python
import asyncio
async def saludar():
    print("¡Hola, mundo!")
    await asyncio.sleep(1)
    print("¡Adiós, mundo!")
asyncio.run(saludar())
```

## **Funciones de programación concurrente**

La programación concurrente se utiliza para ejecutar múltiples tareas al
mismo tiempo. Se pueden utilizar bibliotecas como `threading` o
`multiprocessing` para crear y gestionar hilos o procesos concurrentes.

``` python
import threading
def saludar():
    print("¡Hola, mundo!")
hilo = threading.Thread(target=saludar)
hilo.start()
hilo.join()
print("¡Adiós, mundo!")
```

## **Funciones de programación reactiva**

La programación reactiva se utiliza para gestionar flujos de datos y
eventos de manera asíncrona. Se pueden utilizar bibliotecas como `RxPy`
para crear y gestionar flujos de datos reactivos.

``` python
import rx
from rx import operators as ops
def saludar(nombre):
    print(f"¡Hola, {nombre}!")
nombres = ["Juan", "María", "Pedro"]
rx.from_(nombres) \
    .pipe(ops.map(saludar)) \
    .subscribe()
```

## **Funciones de programación declarativa**

La programación declarativa se utiliza para describir el resultado
deseado sin especificar cómo lograrlo. Se pueden utilizar funciones de
alto nivel y expresiones lambda para definir operaciones de manera más
concisa y legible.

``` python

numeros = [1, 2, 3, 4, 5]
pares = list(filter(lambda x: x % 2 == 0, numeros))
print("Los números pares son:", pares)
```

## **Funciones de programación imperativa**

La programación imperativa se utiliza para describir cómo lograr un
resultado específico mediante una serie de instrucciones secuenciales.
Se pueden utilizar bucles y estructuras de control para definir el flujo
de ejecución del programa.

``` python
numeros = [1, 2, 3, 4, 5]
pares = []
for numero in numeros:
    if numero % 2 == 0:
        pares.append(numero)
print("Los números pares son:", pares)
```

## **Funciones de programación estructurada**

La programación estructurada se utiliza para definir el flujo de
ejecución del programa mediante el uso de funciones y estructuras de
control. Se pueden utilizar funciones para dividir el código en módulos
más pequeños y manejables.

``` python
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        raise ValueError("No se puede dividir por cero")
    return a / b

def calcular(a, b, operacion):
    if operacion == "suma":
        return sumar(a, b)
    
    elif operacion == "resta":
        return restar(a, b)
    
    elif operacion == "multiplicacion":
        return multiplicar(a, b)
    
    elif operacion == "division":
        return dividir(a, b)
    
    else:
        raise ValueError("Operación no válida")
    
resultado = calcular(10, 5, "suma")
print("El resultado de la suma es:", resultado)
resultado = calcular(10, 5, "resta")
print("El resultado de la resta es:", resultado)
resultado = calcular(10, 5, "multiplicacion")
print("El resultado de la multiplicación es:", resultado)
resultado = calcular(10, 5, "division")
print("El resultado de la división es:", resultado)
```

## **Funciones de programación modular**

La programación modular se utiliza para dividir el código en módulos
independientes y reutilizables. Se pueden utilizar funciones para
definir la interfaz de cada módulo y facilitar su uso en otros
programas.

``` python
def sumar(a, b):
    return a + b

def restar(a, b):
    return a - b

def multiplicar(a, b):
    return a * b

def dividir(a, b):
    if b == 0:
        raise ValueError("No se puede dividir por cero")
    return a / b

def calcular(a, b, operacion):
    if operacion == "suma":
        return sumar(a, b)
    elif operacion == "resta":
        return restar(a, b)
    elif operacion == "multiplicacion":
        return multiplicar(a, b)
    elif operacion == "division":
        return dividir(a, b)
    else:
        raise ValueError("Operación no válida")
resultado = calcular(10, 5, "suma")
print("El resultado de la suma es:", resultado)
resultado = calcular(10, 5, "resta")
print("El resultado de la resta es:", resultado)
resultado = calcular(10, 5, "multiplicacion")
print("El resultado de la multiplicación es:", resultado)
resultado = calcular(10, 5, "division")
print("El resultado de la división es:", resultado)
```

## **Funciones de programación orientada a eventos**

La programación orientada a eventos se utiliza para gestionar eventos y
acciones en el programa. Se pueden utilizar funciones de devolución de
llamada (callbacks) para definir cómo responder a eventos específicos,
como clics de botones o cambios en el estado de la aplicación.

``` python
import tkinter as tk

def saludar():
    print("¡Hola, mundo!")
ventana = tk.Tk()
boton = tk.Button(ventana, text="Saludar", command=saludar)
boton.pack()
ventana.mainloop()
```

## **Funciones de programación orientada a aspectos**

La programación orientada a aspectos se utiliza para separar las
preocupaciones transversales del código, como la gestión de errores, la
seguridad o el registro. Se pueden utilizar funciones de aspecto para
definir cómo aplicar estas preocupaciones a diferentes partes del código
sin modificar su lógica principal.

``` python
def registrar(funcion):
    def funcion_registrada(*args, **kwargs):
        print(f"Llamando a la función {funcion.__name__} con argumentos {args} y {kwargs}")
        resultado = funcion(*args, **kwargs)
        print(f"Resultado de la función {funcion.__name__}: {resultado}")
        return resultado
    return funcion_registrada
@registrar

def sumar(a, b):
    return a + b
resultado = sumar(2, 3)
print("El resultado de la suma es:", resultado)
```

## **Funciones de programación orientada a dominio**

La programación orientada a dominio se utiliza para modelar y resolver
problemas específicos de un dominio particular. Se pueden utilizar
funciones para definir el comportamiento y las propiedades de los
objetos en el dominio, facilitando su uso y comprensión.

``` python
class Producto:
    def __init__(self, nombre, precio):
        self.nombre = nombre
        self.precio = precio

    def aplicar_descuento(self, porcentaje):
        self.precio -= self.precio * (porcentaje / 100)
        return self.precio
    
    def __str__(self):
        return f"Producto: {self.nombre}, Precio: {self.precio}"
producto1 = Producto("Camiseta", 20)
producto2 = Producto("Pantalón", 40)
producto1.aplicar_descuento(10)
producto2.aplicar_descuento(20)
print(producto1)
print(producto2)
```

## **Funciones de programación orientada a servicios**

La programación orientada a servicios se utiliza para definir y
gestionar servicios independientes que pueden ser utilizados por
diferentes aplicaciones o sistemas. Se pueden utilizar funciones para
definir la interfaz y el comportamiento de cada servicio, facilitando su
uso y reutilización.

``` python
import requests
def obtener_datos(url):
    response = requests.get(url)
    if response.status_code == 200:
        return response.json()
    else:
        raise ValueError("Error al obtener los datos")
def procesar_datos(datos):
    # Procesar los datos obtenidos
    for item in datos:
        print(item)
url = "https://jsonplaceholder.typicode.com/posts"
datos = obtener_datos(url)
procesar_datos(datos)
```

## **Funciones de programación orientada a microservicios**

La programación orientada a microservicios se utiliza para definir y
gestionar servicios independientes y autónomos que pueden ser utilizados
por diferentes aplicaciones o sistemas. Se pueden utilizar funciones
para definir la interfaz y el comportamiento de cada microservicio,
facilitando su uso y reutilización.

``` python
from flask import Flask, jsonify, request
app = Flask(__name__)
@app.route('/suma', methods=['POST'])
def suma():
    data = request.get_json()
    a = data['a']
    b = data['b']
    resultado = a + b
    return jsonify({'resultado': resultado})
@app.route('/resta', methods=['POST'])

def resta():
    data = request.get_json()
    a = data['a']
    b = data['b']
    resultado = a - b
    return jsonify({'resultado': resultado})
@app.route('/multiplicacion', methods=['POST'])

def multiplicacion():
    data = request.get_json()
    a = data['a']
    b = data['b']
    resultado = a * b
    return jsonify({'resultado': resultado})

@app.route('/division', methods=['POST'])

def division():
    data = request.get_json()
    a = data['a']
    b = data['b']
    if b == 0:
        return jsonify({'error': 'No se puede dividir por cero'}), 400
    resultado = a / b
    return jsonify({'resultado': resultado})

if __name__ == '__main__':
    app.run(debug=True)
```

------------------------------------------------------------------------

# **Funciones Integradas**

``` python
# Imprime texto o resultados en consola
print("Hola, mundo")

# Imprimir varias variables
nombre = "Jesús"
edad = 25
print("Nombre:", nombre, "- Edad:", edad)

# Imprimir con formato
print(f"{nombre} tiene {edad} años")  # Usando f-strings (recomendado)
```

# type(): Muestra el tipo de dato

``` python
# Muestra el tipo de una variable o literal
print(type(10))          # int
print(type(3.14))        # float
print(type("texto"))     # str
print(type(True))        # bool
```

# len(): Longitud de secuencias

``` python
# Devuelve la cantidad de elementos
texto = "Python"
lista = [1, 2, 3, 4]

print(len(texto))  # 6
print(len(lista))  # 4
```

# str(), int(), float(), bool(): Conversión de tipos

``` python
# str(): convierte a cadena
print(str(123))  # "123"

# int(): convierte a entero (si es posible)
print(int("10"))  # 10

# float(): convierte a decimal
print(float("3.14"))  # 3.14

# bool(): convierte a booleano
print(bool(""))    # False
print(bool("Hola"))  # True
```

# sum(), max(), min(): Operaciones numéricas

``` python
numeros = [1, 2, 3, 4, 5]

print(sum(numeros))  # 15
print(max(numeros))  # 5
print(min(numeros))  # 1
```

# input(): Entrada de datos por teclado

``` python
# Captura texto del usuario (devuelve str)
nombre = input("¿Cuál es tu nombre? ")
print("Hola", nombre)
```

# isinstance(): Verificar tipo de dato

``` python
x = 10
print(isinstance(x, int))   # True
print(isinstance(x, float)) # False
```

``` python
# Definición de una función simple
def saludar(nombre):
    return f"Hola, {nombre}!"

# Llamar la función
mensaje = saludar("Jesús")
print(mensaje)
```

# help(): Acceder a la documentación

``` python
# Muestra la documentación de una función u objeto
help(print)    # Descripción de la función print
help(str)      # Información sobre la clase str
```

# Definir funciones

``` python
# Definir una función sin argumentos
def saludar_mundo():
    return "Hola, mundo!"

# Llamar la función
mensaje = saludar_mundo()
```

``` python
# Definición de una función con parámetros
def sumar(a, b):
    return a + b

# Llamar la función
resultado = sumar(5, 10)
print("La suma es:", resultado)
```