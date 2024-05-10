# Join

`join` es un potente comando de procesamiento de texto en Linux. Te permite combinar líneas de dos archivos en un campo común, lo que funciona de forma similar a la operación `join` en SQL. Resulta especialmente útil cuando se trabaja con grandes volúmenes de datos. En concreto, `join` utiliza las líneas de dos ficheros para formar líneas que contengan pares de líneas relacionadas de forma significativa.

Por ejemplo, si tienes dos ficheros que contienen una lista de artículos, uno con costes y otro con cantidades, puedes utilizar `join` para combinar estos dos ficheros de forma que cada artículo tenga un coste y una cantidad en la misma línea.

```bash
# Syntax
join file1.txt file2.txt
```

Tenga en cuenta que el comando `join` sólo funciona correctamente cuando los archivos están ordenados. 
Es crucial entender todas las opciones y banderas proporcionadas para utilizar `join` con eficacia en las tareas de procesamiento de texto.