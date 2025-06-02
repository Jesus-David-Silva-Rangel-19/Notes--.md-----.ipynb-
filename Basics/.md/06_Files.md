# Python: Manejos de arhivos

# Manejo de Archivos en Python

El manejo de archivos en Python es una tarea común que permite leer, escribir y manipular datos almacenados en archivos. Python proporciona una interfaz sencilla para trabajar con archivos, lo que facilita la lectura y escritura de datos en diferentes formatos.

## Abrir un archivo

Para trabajar con archivos, primero debes abrirlos utilizando la función `open()`. Esta función toma dos argumentos: el nombre del archivo y el modo de apertura. Los modos más comunes son:

- `'r'`: Modo de lectura (por defecto). Abre el archivo para leer su contenido.

- `'w'`: Modo de escritura. Crea un nuevo archivo o sobrescribe uno existente.

- `'a'`: Modo de anexado. Abre el archivo para agregar contenido al final sin sobrescribirlo.

- `'b'`: Modo binario. Se utiliza para leer o escribir archivos en formato binario.

**Ejemplos:**

```python
# Abrir un archivo en modo lectura
archivo = open('mi_archivo.txt', 'r')

# Abrir un archivo en modo escritura
archivo_escritura = open('mi_archivo.txt', 'w')

# Abrir un archivo en modo anexado
archivo_anexado = open('mi_archivo.txt', 'a')
```

## Lectura de archivo CSV

Para trabajar con archivos CSV (Comma-Separated Values), puedes utilizar el módulo `csv` de Python, que proporciona funciones para leer y escribir archivos CSV de manera sencilla.

```python
import csv

# Escribir en un archivo CSV
with open('datos.csv', 'w', newline='') as archivo_csv:
    escritor = csv.writer(archivo_csv)
    escritor.writerow(['Nombre', 'Edad'])
    escritor.writerow(['Alice', 30])
    escritor.writerow(['Bob', 25])

# Leer un archivo CSV
with open('datos.csv', 'r') as archivo_csv:
    lector = csv.reader(archivo_csv)
    for fila in lector:
        print(fila)
```

**Salida:**
```
['Nombre', 'Edad']
['Alice', '30']
['Bob', '25']
```

## Escritura de archivos CSV

Para escribir datos en un archivo CSV, puedes utilizar el módulo `csv` y su clase `writer`. Puedes escribir filas de datos utilizando el método `writerow()`.

```python
import csv

# Escribir en un archivo CSV
with open('datos.csv', 'w', newline='') as archivo_csv:
    escritor = csv.writer(archivo_csv)
    escritor.writerow(['Nombre', 'Edad'])
    escritor.writerow(['Alice', 30])
    escritor.writerow(['Bob', 25])
```

# Pandas

Pandas es una biblioteca de Python que proporciona estructuras de datos y herramientas para el análisis de datos. Es especialmente útil para trabajar con datos tabulares, como archivos CSV, Excel y bases de datos SQL.

## Lectura de archivos CSV con Pandas
```python
import pandas as pd

# Leer un archivo CSV
df = pd.read_csv('datos.csv')
print(df)
```
**Salida:**

```
   Nombre  Edad
0  Alice    30
1    Bob    25
```

## Lectura de diferentes formatos de archivo con Pandas

Pandas puede leer y escribir en varios formatos de archivo, incluyendo CSV, Excel, JSON y más. Aquí hay algunos ejemplos:

```python
# Leer un archivo Excel
df_excel = pd.read_excel('datos.xlsx')

# Leer un archivo JSON
df_json = pd.read_json('datos.json')

# Leer un archivo de texto delimitado
df_txt = pd.read_csv('datos.txt', delimiter='\t')  # Usando tabulaciones como delimitador

# Leer un archivo SQL
df_sql = pd.read_sql('SELECT * FROM tabla', conexion_a_base_de_datos)
```

## Escribir un DataFrame en un archivo CSV

```python
# Escribir un DataFrame en un archivo CSV
df.to_csv('datos_nuevos.csv', index=False)
```

> **Descripción:** Este ejemplo muestra cómo declarar un diccionario que almacena información relacionada y su tipo.

> **Salida:** `{'nombre': 'Juan', 'edad': 30, 'ciudad': 'Madrid'} <class 'dict'>`

# Cerrar un archivo
Es importante cerrar un archivo después de haber terminado de trabajar con él para liberar recursos del sistema. Puedes hacerlo utilizando el método `close()` o, preferiblemente, utilizando la declaración `with`, que cierra automáticamente el archivo al salir del bloque.

```python
# Cerrar un archivo
archivo.close()

# Usar la declaración with para abrir un archivo
with open('mi_archivo.txt', 'r') as archivo:
    contenido = archivo.read()

# El archivo se cierra automáticamente al salir del bloque
```

> **Descripción:** Este ejemplo muestra cómo abrir un archivo utilizando la declaración `with`, que garantiza que el archivo se cierre automáticamente al finalizar el bloque.

>**Nota:** Es recomendable utilizar la declaración `with` para manejar archivos, ya que asegura que el archivo se cierre correctamente, incluso si ocurre un error durante la lectura o escritura.


## Manejo de excepciones al trabajar con archivos

Es importante manejar excepciones al trabajar con archivos para evitar errores inesperados. Puedes utilizar bloques `try` y `except` para capturar errores al abrir, leer o escribir archivos.

```python
try:
    with open('mi_archivo.txt', 'r') as archivo:
        contenido = archivo.read()
except FileNotFoundError:
    print("El archivo no existe.")
except IOError:
    print("Error al leer el archivo.")
```

> **Descripción:** Este ejemplo muestra cómo manejar excepciones al intentar abrir un archivo que no existe o al leer un archivo con problemas de entrada/salida.

> **Salida:** Si el archivo no existe, se mostrará el mensaje "El archivo no existe." Si hay un error de entrada/salida, se mostrará "Error al leer el archivo."

# Trabajar con rutas de acceso y directorios

Para trabajar con rutas de acceso y directorios, puedes utilizar el módulo `os` de Python. Este módulo proporciona funciones para manipular rutas de archivos y directorios de manera independiente del sistema operativo.

```python
import os

# Obtener el directorio actual
directorio_actual = os.getcwd()

print("Directorio actual:", directorio_actual)

# Cambiar al directorio deseado
os.chdir('/ruta/al/directorio')
print("Nuevo directorio actual:", os.getcwd())

# Listar archivos en un directorio
archivos = os.listdir('.')
print("Archivos en el directorio:", archivos)

# Crear un nuevo directorio
os.mkdir('nuevo_directorio')

# Eliminar un archivo
os.remove('archivo_a_eliminar.txt')

# Eliminar un directorio
os.rmdir('directorio_a_eliminar')
```

> **Descripción:** Este ejemplo muestra cómo utilizar el módulo `os` para trabajar con rutas de acceso y directorios, incluyendo la obtención del directorio actual, el cambio de directorio, la lista de archivos, la creación y eliminación de directorios y archivos.

# Trabajar con archivos y directorios en Pandas

Pandas también proporciona funciones para trabajar con archivos y directorios. Puedes utilizar `pandas.read_csv()` para leer archivos CSV y `DataFrame.to_csv()` para escribir DataFrames en archivos CSV.

```python
import pandas as pd

# Leer un archivo CSV
df = pd.read_csv('datos.csv')
print(df)

# Escribir un DataFrame en un archivo CSV
df.to_csv('datos_nuevos.csv', index=False)

# Leer un archivo Excel
df_excel = pd.read_excel('datos.xlsx')
print(df_excel)

# Escribir un DataFrame en un archivo Excel
df_excel.to_excel('datos_nuevos.xlsx', index=False)

# Leer un archivo JSON
df_json = pd.read_json('datos.json')
print(df_json)

# Escribir un DataFrame en un archivo JSON
df_json.to_json('datos_nuevos.json', orient='records', lines=True)

# Escribir un DataFrame en un archivo de texto delimitado
df.to_csv('datos_nuevos.txt', sep='\t', index=False)

# Leer un archivo de texto delimitado
df_txt = pd.read_csv('datos.txt', delimiter='\t')
print(df_txt)

# Escribir un DataFrame en una base de datos SQL
df.to_sql('tabla_nueva', conexion_a_base_de_datos, if_exists='replace', index=False)

# Leer un DataFrame desde una base de datos SQL
df_sql = pd.read_sql('SELECT * FROM tabla', conexion_a_base_de_datos)
print(df_sql)
```

> **Descripción:** Este ejemplo muestra cómo utilizar Pandas para leer y escribir archivos en diferentes formatos, incluyendo CSV, Excel, JSON y texto delimitado, así como trabajar con bases de datos SQL.

> **Salida:** La salida mostrará el contenido de los DataFrames leídos desde los archivos y confirmará la escritura exitosa de los nuevos archivos.

# Resumen

El manejo de archivos en Python es una habilidad esencial para trabajar con datos. Puedes abrir, leer, escribir y manipular archivos de manera sencilla utilizando las funciones integradas de Python y bibliotecas como `csv` y `pandas`. Además, es importante manejar excepciones y utilizar el módulo `os` para trabajar con rutas de acceso y directorios. Con estas herramientas, puedes realizar tareas de procesamiento de datos de manera eficiente y efectiva.