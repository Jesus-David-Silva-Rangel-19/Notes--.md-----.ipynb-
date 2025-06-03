# Python: Indexación y Segmentación

# Indexación

La indexación es el proceso de acceder a elementos específicos dentro de una estructura de datos, como listas, tuplas o cadenas de texto. En Python, los índices comienzan en $0$, lo que significa que el primer elemento tiene un índice de $0$, el segundo elemento tiene un índice de $1$, y así sucesivamente.

**Ejemplo de indexación:**

```python
mi_lista = [10, 20, 30, 40, 50]
print("Primer elemento:", mi_lista[0])
print("Segundo elemento:", mi_lista[1])
```
> **Descripción:** Este ejemplo muestra cómo acceder a los elementos de una lista utilizando sus índices.

**Salida:** La salida será:


```
Primer elemento: 10
Segundo elemento: 20
```

>**Nota:** Si intentas acceder a un índice que está fuera del rango de la lista, obtendrás un error `IndexError`.


**Ejemplo de error de índice:**

```python
mi_lista = [10, 20, 30, 40, 50]
print("Elemento fuera de rango:", mi_lista[5])  # Esto generará un IndexError
```
> **Descripción:** Este ejemplo muestra un intento de acceder a un índice fuera del rango de la lista, lo que generará un error.

**Salida del error:**

```
IndexError: list index out of range
```

# Segmentación

La segmentación, también conocida como "slicing", permite extraer una porción de una estructura de datos. Puedes especificar un rango de índices para obtener una sublista, subcadena, etc. La sintaxis básica es `estructura[inicio:fin]`, donde `inicio` es el índice del primer elemento que deseas incluir y `fin` es el índice del primer elemento que no deseas incluir.

**Ejemplo de segmentación:**

```python
mi_lista = [10, 20, 30, 40, 50]

sub_lista = mi_lista[1:4]  # Extrae elementos desde el índice 1 hasta el 3 (el 4 no se incluye)

print("Sublista:", sub_lista)
```
> **Descripción:** Este ejemplo muestra cómo extraer una sublista utilizando segmentación.

**Salida:** La salida será:

```
Sublista: [20, 30, 40]
```
> **Nota:** Si omites el índice de inicio, se asumirá que es $0$, y si omites el índice de fin, se asumirá que es el final de la lista.

> Si deseas extraer todos los elementos desde un índice específico hasta el final, puedes usar `estructura[inicio:]`.

> Si deseas extraer todos los elementos desde el inicio hasta un índice específico, puedes usar `estructura[:fin]`.
