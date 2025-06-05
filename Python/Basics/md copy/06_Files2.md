# 🗂️ **Manejo de Archivos en Python**

## 📌 **¿Qué es?**

El **manejo de archivos** en Python hace referencia al conjunto de
operaciones que permiten **abrir, leer, escribir, modificar y cerrar
archivos** dentro de un programa. Estas operaciones permiten al software
interactuar con el sistema de archivos del sistema operativo.

Los archivos pueden ser de texto (`.txt`, `.csv`, `.log`) o binarios
(`.jpg`, `.pdf`, `.mp3`), y Python ofrece herramientas integradas para
trabajar con ambos tipos.


## 🎯 **¿Para qué se usa?**

- **Almacenar datos** generados por un programa.
- **Leer datos externos** para su procesamiento.
- **Guardar resultados** de cálculos o informes.
- **Automatizar tareas** relacionadas con archivos (renombrar,
  clasificar, convertir, etc.).


## 🧠 **¿Por qué es importante?**

El manejo de archivos permite:

- **Persistencia de datos** más allá de la ejecución del programa.
- **Intercambio de información** entre distintos sistemas o aplicaciones.
- **Acceso a bases de datos simples**, como archivos `.csv`.
- **Gestión automatizada de documentos**, fundamental en scripts de automatización y análisis de datos.


## 🧱 **Estructura general en Python**

Python ofrece la función integrada `open()` para acceder a archivos. La
sintaxis básica es la siguiente:

``` python
archivo = open("nombre_archivo.txt", "modo")
# operaciones de lectura o escritura
archivo.close()
```

### **Modos de apertura:**

- `"r"` → lectura (modo por defecto).
- `"w"` → escritura (crea o sobreescribe).
- `"a"` → agregar al final del archivo.
- `"rb"` / `"wb"` → modo binario.

**Alternativamente**, se recomienda usar el bloque `with` que cierra
automáticamente el archivo:

``` python
with open("archivo.txt", "r") as archivo:
    contenido = archivo.read()
```


## 🧪 **Ejemplos prácticos**

### 📖 **Leer un archivo de texto**

``` python
with open("datos.txt", "r") as archivo:
    contenido = archivo.read()
    print(contenido)
```

### 📝 **Escribir en un archivo**

``` python
with open("resultado.txt", "w") as archivo:
    archivo.write("Este es un archivo generado por Python.")
```

### ➕ **Agregar contenido sin borrar el existente**

``` python
with open("registro.txt", "a") as archivo:
    archivo.write("\nNueva línea agregada.")
```

### 🔁 **Leer línea por línea**

``` python
with open("log.txt", "r") as archivo:
    for linea in archivo:
        print(linea.strip())
```


## 💡 **Recomendaciones**

- Siempre verificar si el archivo existe antes de abrirlo en modo
  lectura.
- Usar `try-except` para manejar errores como `FileNotFoundError`.
- Preferir `with open(...)` para evitar olvidarse de cerrar archivos.
- Controlar correctamente los **modos de apertura** para evitar
  sobreescrituras accidentales.


## 📚 **Referencias**

- [Documentación oficial de `open()` –
  Python](https://docs.python.org/3/library/functions.html#open)
- [Lectura y escritura de archivos – Python
  Docs](https://docs.python.org/3/tutorial/inputoutput.html#reading-and-writing-files)