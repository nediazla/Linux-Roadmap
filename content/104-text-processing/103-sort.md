# Sort 

Linux proporciona una variedad de herramientas para procesar y manipular archivos de texto, una de las cuales es el comando «sort». El comando `sort` en Linux se utiliza para ordenar el contenido de un archivo de texto, línea por línea. El comando utiliza valores ASCII para ordenar archivos. Puede utilizar este comando para ordenar los datos de un archivo de diferentes maneras, como alfabéticamente, numéricamente, en orden inverso o incluso mensualmente. El comando sort toma un fichero como entrada e imprime el contenido ordenado en la salida estándar (pantalla).

A continuación se muestra un uso básico del comando `sort`:

```bash
sort filename.txt
```

Este comando imprime el contenido ordenado del archivo `filename.txt`. El contenido original del archivo no se modifica. Para volver a guardar el contenido ordenado en el archivo, puede utilizar la redirección:

```bash
sort filename.txt > sorted_filename.txt
```

Este comando ordena el contenido de `filename.txt` y redirige el contenido ordenado a `sorted_filename.txt`.