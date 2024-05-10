# Enlaces Soft y Hard 

En sistemas operativos tipo Unix como Linux, los enlaces blandos (simbólicos) y duros son simplemente referencias a ficheros existentes que permiten a los usuarios crear atajos y efectos de duplicación dentro de su sistema de ficheros. 

Un enlace duro es un reflejo especular del archivo original, compartiendo los mismos datos de archivo pero mostrando un nombre y un número de inodo diferentes. Es vital tener en cuenta que si se elimina el archivo original, el enlace duro sigue conservando los datos del archivo. 

Por otro lado, un enlace blando, también conocido como enlace simbólico, es más como un acceso directo al archivo original. Tiene un número de nodo diferente y los datos del archivo sólo residen en el archivo original. Si se elimina el archivo original, el enlace simbólico se rompe y no funcionará hasta que se restaure el archivo original.

A continuación se muestra un ejemplo de cómo crear un enlace blando y un enlace duro en Linux:

```bash
# Create a hard link
ln source_file.txt hard_link.txt

# Create a soft link
ln -s source_file.txt soft_link.txt
```

Por favor, entienda que `source_file.txt` es el archivo original y `hard_link.txt` & `soft_link.txt` son los enlaces hard y soft respectivamente.