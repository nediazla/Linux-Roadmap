# Uniq
 
En Linux, `uniq` es un programa de línea de comandos extremadamente útil para el tratamiento de textos. Ayuda a examinar y manipular archivos de texto comparando o filtrando las líneas repetidas que son adyacentes. Tanto si se trata de una lista de datos como de un documento de texto de gran tamaño, el comando `uniq` permite encontrar y filtrar líneas duplicadas, o incluso proporcionar un recuento de cada línea única de un archivo. Es importante recordar que `uniq` sólo elimina los duplicados que están uno al lado del otro, por lo que para sacar el máximo provecho de este comando, los datos suelen ordenarse utilizando primero el comando `sort`.

Un ejemplo de uso de `uniq` sería:

```bash
sort names.txt | uniq
```

En este ejemplo, `nombres.txt` es un fichero que contiene una lista de nombres. El comando `sort` ordena todas las líneas del archivo y, a continuación, el comando `uniq` elimina todas las líneas duplicadas. La salida resultante sería una lista de nombres únicos de `names.txt`.