# Head 

El comando `head` en Linux es una utilidad de procesamiento de texto que permite al usuario mostrar la primera parte (o la «cabeza») de los archivos. Se utiliza habitualmente para previsualizar el inicio de un fichero sin cargar todo el documento en memoria, lo que puede resultar una forma eficaz de examinar rápidamente los datos de ficheros muy grandes. Por defecto, el comando `head` imprime las 10 primeras líneas de cada fichero en la salida estándar, que es el terminal en la mayoría de los sistemas.

```bash
head file.txt
```

El número de líneas de salida puede personalizarse utilizando una opción. Por ejemplo, para mostrar las 5 primeras líneas, se utiliza la opción `-n` seguida del número de líneas:

```bash
head -n 5 file.txt
```