# Guía de referencia: Importar conjuntos de datos con Python

## Cómo importar un conjunto de datos desde un Archivo CSV

Hay varias formas de importar un Archivo CSV a Python, pero sólo revisaremos algunas de las más comunes. Comience por utilizar una sentencia `with` y la función `open()`. Pase el nombre del archivo (o la ruta del archivo ) del Archivo CSV a la función `open()` junto con un argumento para el parámetro `mode` de la función.

`with open("file path/file name", mode=)`

Así que la sintaxis hasta ahora es

**Nota:** El siguiente bloque de código no es interactivo.

```python
with open("file path/file name", mode=)
```

El modo le está diciendo a la librería Python qué hacer con el archivo. Cuando se define el modo, se utiliza una de las siguientes opciones:

- 'r' - read

- 'w' - escribir

- 'a' - añadir

- '+' - crear nuevo archivo

Típicamente, estarás definiendo el modo dentro del campo de argumento with `open()` como 'r' porque quieres que Python abra y lea el Archivo CSV.

A continuación, añadiremos `as file` al final, para asignar el resultado a un nombre de variable. En este caso, la llamaremos data.

Nota: El siguiente bloque de código no es interactivo.

```Python
with open("file path/file name", mode='r') as file:
    data = file.read()
```

En este bloque de código, hemos abierto el Archivo CSV en modo de lectura y hemos asignado su contenido a la variable `data`. Ahora, `data` contiene el contenido del Archivo CSV como una cadena de texto.
