# Permisos de Archivos en Linux

En los sistemas Linux, los derechos y privilegios se asignan a archivos y directorios en forma de permisos. Estos permisos indican quién puede leerlos, escribirlos o ejecutarlos (correrlos). En Linux, hay tres tipos de usuarios: propietarios, grupos y otros que pueden tener un conjunto diferente de permisos.

De hecho, los permisos en el sistema están ahí por una razón: evitar que los usuarios sin privilegios realicen cambios en el sistema que, en última instancia, afectarían a otros usuarios. Con los permisos adecuados, los usuarios sin privilegios pueden hacer cambios que serían beneficiosos o inofensivos para el sistema Linux. 

Veamos un ejemplo:

```bash
-rwxr--r-- 1 root root 4096 Jan 1 12:00 filename
```

En el ejemplo anterior, el primer carácter `-` indica si se trata de un archivo normal(`-`) o de un directorio(`d`). El siguiente grupo de tres caracteres(`rwx`) representa los permisos para el propietario del fichero. Los siguientes tres caracteres(`r--`) representan los permisos para el grupo y el último grupo de tres caracteres(`r--`) representa los permisos para otros. 

La `r` indica que el archivo puede ser leído, `w` indica que el archivo puede ser escrito, y `x` indica que el archivo puede ser ejecutado.

Los permisos pueden cambiarse usando los comandos `chmod`, `chown` y `chgrp`.