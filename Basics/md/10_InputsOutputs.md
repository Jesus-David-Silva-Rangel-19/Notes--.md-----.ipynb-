
# 🔁 **Inputs y Outputs en Python**

## 📌 **¿Qué son?**

Los **Inputs (entradas)** y **Outputs (salidas)** en Python son los
mecanismos fundamentales que permiten la **interacción entre el usuario
y el programa**. Permiten **recibir datos desde el exterior** (input) y
**mostrar resultados o información** (output).


## 🎯 **¿Qué funciones desempeñan?**

- **Input**: Permite al usuario **proporcionar datos al programa**
  durante su ejecución.
- **Output**: Permite al programa **mostrar resultados, mensajes,
  errores o información útil al usuario**.


## ⚙️ **¿Para qué se usan?**

- **Captura de datos dinámicos** (por ejemplo: edad, nombre, opciones
  del usuario).
- **Comunicación con el usuario final** mediante mensajes explicativos o
  resultados.
- **Validación y procesamiento de datos ingresados**.
- **Seguimiento del estado de ejecución** (debugging, trazas, etc.).


## 🧠 **¿Por qué son importantes?**

- Permiten la **interactividad del software**.
- Facilitan el **flujo de información** entre el sistema y el usuario.
- Son esenciales para **crear programas funcionales, personalizables y
  reutilizables**.
- Constituyen la base de interfaces, formularios y automatizaciones.


## 🧱 **Estructura de Inputs y Outputs en Python**

### 🔹 **Entrada de datos (input)**

``` python
variable = input("Mensaje al usuario: ")
```

- Siempre devuelve una **cadena de texto** (`str`).
- Se puede convertir a otros tipos: `int()`, `float()`, etc.

### 🔹 **Salida de datos (print)**

``` python
print("Mensaje o contenido a mostrar")
```

- Permite **mostrar uno o varios elementos**.
- Acepta variables, textos, resultados de operaciones, etc.


## 🧪 **Ejemplos prácticos**

### **Ejemplo 1: Entrada y salida básica**

``` python
nombre = input("¿Cuál es tu nombre? ")
print("Hola,", nombre)
```

### **Ejemplo 2: Conversión de tipos**

``` python
edad = int(input("Ingrese su edad: "))
print("Tendrás", edad + 1, "años el próximo año.")
```

### **Ejemplo 3: Concatenación y formato**

``` python
producto = input("Producto: ")
precio = float(input("Precio ($): "))
print(f"El producto {producto} cuesta ${precio:.2f}")
```

### **Ejemplo 4: Múltiples entradas**

``` python
a = int(input("Primer número: "))
b = int(input("Segundo número: "))
print("Suma:", a + b)
```


## 💡 **Consejos prácticos**

- Validar siempre el tipo de dato ingresado por el usuario.
- Utilizar `try-except` para capturar errores en la conversión de tipos.
- Emplear `f-strings` (`f""`) para mejorar la legibilidad de las
  salidas.
- Documentar claramente qué datos se esperan del usuario.


## 📚 **Referencias**

- [Función `input()` – Python
  Docs](https://docs.python.org/3/library/functions.html#input)
- [Función `print()` – Python
  Docs](https://docs.python.org/3/library/functions.html#print)

------------------------------------------------------------------------