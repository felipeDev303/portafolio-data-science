## DataFrame.head()

- El método `head()` mostrará las primeras n filas del marco de datos.

- En el campo de argumentos, introduce el número de filas que quieres que se muestren en un Notebook de Python. Por defecto son 5 filas.

```python
# Mostrar las primeras 10 filas del marco de datos
df.head(10)
```

**Nota:** En un cuaderno Python, los resultados de `head()` no incluirán una tabla con líneas de cuadrícula visibles.

### DataFrame.info(X)

- El método `info()` mostrará un resumen del dataframe, incluyendo el índice de rango, dtypes, cabeceras de columna y uso de memoria.

- Si se deja en blanco el campo de argumentos, se obtendrá un resumen completo. Como opción, en el campo de argumentos puede escribir `show_counts=True`, que devolverá el recuento de valores no nulos para cada columna.

```python
# Resumen del marco de datos
df.info(X)
```

### DataFrame.describe()

- El método `describe()` devolverá estadísticas descriptivas de todo el conjunto de datos, incluyendo recuento total, media, mínimo, máximo, dispersión y distribución.

- Si deja el campo de argumentos en blanco, devolverá por defecto un resumen de las estadísticas del marco de datos. Como opción, puede utilizar "include=[X]" y "exclude=[X]", que limitarán los resultados a tipos de datos específicos, dependiendo de lo que introduzca entre paréntesis.

```python
# Resumen de estadísticas para todo el marco de datos
df_joined.describe()
```

### DataFrame.shape

- shape es un atributo que devuelve una tupla que representa las dimensiones del dataframe por número de filas y columnas. Recuerde que los atributos no van seguidos de paréntesis. El código será algo parecido a esto

```python
# Obtener el número de filas y columnas del marco de datos
df.shape
```
