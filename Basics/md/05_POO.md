# Python: Programación Orientada a Objetos (POO) para Data Science

# Clases y Objetos

En Python, la Programación Orientada a Objetos (POO) se basa en la creación de clases y objetos. Una clase es una plantilla que define las propiedades y comportamientos de un objeto, mientras que un objeto es una instancia de una clase.

**Definición:**

- **Clase**: Una clase es una estructura que define un tipo de objeto. Contiene atributos (propiedades) y métodos (funciones) que describen el comportamiento del objeto.

- **Objeto**: Un objeto es una instancia de una clase. Cada objeto tiene sus propios valores para los atributos definidos en la clase.

## Ejemplo de clase y objeto

```python
class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre  # Atributo de instancia
        self.edad = edad      # Atributo de instancia

    def saludar(self):
        print(f"Hola, mi nombre es {self.nombre} y tengo {self.edad} años.")

# Crear un objeto de la clase Persona
persona1 = Persona("Juan", 30)
persona1.saludar()  # Llamar al método saludar del objeto persona1
```

> **Descripción:** Este ejemplo define una clase `Persona` con un constructor (`__init__`) que inicializa los atributos `nombre` y `edad`. Luego, se crea un objeto `persona1` de la clase `Persona` y se llama al método `saludar`.

> **Salida:** La salida será:
```plaintext
Hola, mi nombre es Juan y tengo 30 años.
```

## Herencia

La herencia es un principio fundamental de la POO que permite crear nuevas clases basadas en clases existentes. La clase nueva (subclase) hereda los atributos y métodos de la clase base (superclase).

**Definición:**

- **Herencia**: Es el mecanismo que permite que una clase herede atributos y métodos de otra clase. Esto promueve la reutilización del código y la creación de jerarquías de clases.

## Ejemplo de herencia

```python
class Empleado(Persona):  # Empleado hereda de Persona
    def __init__(self, nombre, edad, puesto):
        super().__init__(nombre, edad)  # Llamar al constructor de la clase base
        self.puesto = puesto  # Atributo adicional

    def mostrar_informacion(self):
        print(f"Nombre: {self.nombre}, Edad: {self.edad}, Puesto: {self.puesto}")

# Crear un objeto de la clase Empleado
empleado1 = Empleado("Ana", 28, "Ingeniera de Datos")
empleado1.mostrar_informacion()  # Llamar al método mostrar_informacion del objeto empleado1
```

> **Descripción:** Este ejemplo define una clase `Empleado` que hereda de la clase `Persona`. La clase `Empleado` agrega un nuevo atributo `puesto` y un método `mostrar_informacion`.

**Salida:** La salida será:
```plaintext
Nombre: Ana, Edad: 28, Puesto: Ingeniera de Datos
```

## Polimorfismo

El polimorfismo es otro principio clave de la POO que permite que diferentes clases implementen métodos con el mismo nombre, pero con comportamientos diferentes. Esto permite que el mismo método se pueda llamar en diferentes objetos, y cada objeto responderá de manera adecuada según su propia implementación.

**Definición:**

- **Polimorfismo**: Es la capacidad de diferentes clases de responder al mismo método de manera diferente. Esto se logra mediante la redefinición de métodos en las subclases.

## Ejemplo de polimorfismo

```python
class Animal:
    def hacer_sonido(self):
        pass  # Método abstracto

class Perro(Animal):
    def hacer_sonido(self):
        return "Guau"

class Gato(Animal):
    def hacer_sonido(self):
        return "Miau"

# Crear objetos de las clases Perro y Gato
perro = Perro()
gato = Gato()

# Llamar al método hacer_sonido en ambos objetos
print(perro.hacer_sonido())  # Salida: Guau
print(gato.hacer_sonido())   # Salida: Miau
```

> **Descripción:** Este ejemplo define una clase base `Animal` con un método abstracto `hacer_sonido`. Las clases `Perro` y `Gato` implementan este método de manera diferente, demostrando el polimorfismo.

> **Salida:** La salida será:
```plaintext
Guau
Miau
```

## Encapsulamiento

El encapsulamiento es el principio de ocultar los detalles internos de una clase y exponer solo lo necesario a través de métodos públicos. Esto ayuda a proteger los datos y a mantener la integridad del objeto.

**Definición:**

- **Encapsulamiento**: Es el mecanismo que restringe el acceso directo a los atributos y métodos de una clase, permitiendo que solo se acceda a ellos a través de métodos públicos. Esto ayuda a proteger los datos y a evitar modificaciones no deseadas.

- **Atributos privados**: En Python, los atributos que comienzan con un guion bajo (`_`) se consideran privados y no deben ser accedidos directamente desde fuera de la clase.

- **Métodos públicos**: Los métodos que no comienzan con un guion bajo son considerados públicos y pueden ser llamados desde fuera de la clase.

- **Métodos privados**: Los métodos que comienzan con un guion bajo (`_`) se consideran privados y no deben ser llamados desde fuera de la clase.

- **Métodos protegidos**: Los métodos que comienzan con dos guiones bajos (`__`) son considerados protegidos y no deben ser llamados desde fuera de la clase, pero pueden ser accedidos por subclases.

- **Propiedades**: Las propiedades son una forma de controlar el acceso a los atributos de una clase, permitiendo definir métodos para obtener y establecer valores de manera controlada.

- **Decoradores de propiedades**: Los decoradores `@property` y `@<nombre>.setter` se utilizan para definir propiedades en una clase, permitiendo un acceso controlado a los atributos.

## Tipos de atributos y métodos

Los atributos y métodos en Python pueden clasificarse en diferentes tipos según su visibilidad y propósito:

**Atributos:**

- **Atributos públicos**: Son accesibles desde fuera de la clase y no tienen restricciones de acceso. Se definen sin guiones bajos.

- **Atributos privados**: Son accesibles solo desde dentro de la clase y no deben ser accedidos directamente desde fuera. Se definen con un guion bajo al principio (`_atributo`).

- **Atributos protegidos**: Son accesibles desde dentro de la clase y sus subclases, pero no deben ser accedidos directamente desde fuera. Se definen con dos guiones bajos al principio (`__atributo`).

**Métodos:**

- **Métodos públicos**: Son accesibles desde fuera de la clase y no tienen restricciones de acceso. Se definen sin guiones bajos.

- **Métodos privados**: Son accesibles solo desde dentro de la clase y no deben ser llamados desde fuera. Se definen con un guion bajo al principio (`_metodo`).

- **Métodos protegidos**: Son accesibles desde dentro de la clase y sus subclases, pero no deben ser llamados desde fuera. Se definen con dos guiones bajos al principio (`__metodo`).

# Ejemplo de encapsulamiento

```python
class CuentaBancaria:
    def __init__(self, titular, saldo_inicial):
        self.titular = titular  # Atributo público
        self.__saldo = saldo_inicial  # Atributo privado

    def depositar(self, cantidad):
        if cantidad > 0:
            self.__saldo += cantidad
            print(f"Depósito exitoso. Nuevo saldo: {self.__saldo}")
        else:
            print("Cantidad inválida para depositar.")

    def retirar(self, cantidad):
        if 0 < cantidad <= self.__saldo:
            self.__saldo -= cantidad
            print(f"Retiro exitoso. Nuevo saldo: {self.__saldo}")
        else:
            print("Cantidad inválida para retirar.")

    def obtener_saldo(self):
        return self.__saldo  # Método público para acceder al saldo

# Crear un objeto de la clase CuentaBancaria
cuenta = CuentaBancaria("Juan", 1000)
cuenta.depositar(500)  # Depositar dinero
cuenta.retirar(200)  # Retirar dinero

print("Saldo actual:", cuenta.obtener_saldo())  # Obtener el saldo actual
```

> **Descripción:** Este ejemplo define una clase `CuentaBancaria` que encapsula los detalles de una cuenta bancaria. Los atributos y métodos están diseñados para proteger el saldo de la cuenta y permitir operaciones controladas.

**Salida:** La salida será:
```plaintext
Depósito exitoso. Nuevo saldo: 1500
Retiro exitoso. Nuevo saldo: 1300
Saldo actual: 1300
```

# Resumen

La Programación Orientada a Objetos (POO) en Python es una forma poderosa de organizar y estructurar el código. Los conceptos clave incluyen:

- **Clases**: Plantillas para crear objetos que encapsulan datos y comportamientos.
  
- **Objetos**: Instancias de clases que contienen atributos y métodos.

- **Herencia**: Mecanismo que permite crear nuevas clases a partir de clases existentes.

- **Polimorfismo**: Capacidad de diferentes clases para ser tratadas como instancias de la misma clase a través de una interfaz común.
  
- **Encapsulamiento**: Práctica de ocultar los detalles internos de una clase y exponer solo lo necesario a través de métodos públicos.