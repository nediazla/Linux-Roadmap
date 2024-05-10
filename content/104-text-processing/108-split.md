# Split

Linux proporciona un amplio conjunto de herramientas para manipular datos de texto. Una de estas utilidades es el comando `split` que se utiliza, como su nombre indica, para dividir archivos grandes en archivos más pequeños. El comando `split` en Linux divide un archivo en múltiples partes iguales, basándose en las líneas o bytes especificados por el usuario.

Es un comando útil por su aplicabilidad práctica. Por ejemplo, si tienes un archivo de datos grande que no puede ser usado eficientemente debido a su tamaño, entonces el comando `split` puede ser usado para dividir el archivo en partes más manejables. 

La sintaxis básica del comando `split` es:

```bash
split [options] [input [prefix]]
```

Por defecto, el comando `split` divide el fichero en ficheros más pequeños de 1000 líneas cada uno. Si no se proporciona ningún fichero de entrada, o si se proporciona como -l, lee de la entrada estándar. 

Por ejemplo, para dividir un fichero llamado `ficherogrande.txt` en ficheros de 500 líneas cada uno, el comando sería:

```bash
split -l 500 bigfile.txt 
```