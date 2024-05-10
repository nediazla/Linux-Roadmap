# Permisos bajo gestión de usuarios

Linux, como todos los sistemas tipo Unix, es un sistema multiusuario, lo que significa que puede ser utilizado por varios usuarios al mismo tiempo. Como tal, cuenta con un completo sistema de gestión de permisos para estos usuarios. Estos permisos de Linux dictan quién puede acceder, modificar y ejecutar archivos y directorios.

Los permisos se clasifican en tres tipos:

1. **Permiso de lectura**: los usuarios con permisos de lectura pueden ver el contenido del archivo.

2. **Permiso de escritura**: los usuarios con permisos de escritura pueden modificar el contenido del archivo o directorio.

3. **Permiso de ejecución**: los usuarios con permisos de ejecución pueden ejecutar un archivo o recorrer un directorio.

Estos permisos se pueden configurar para tres tipos de entidades:

1. **Usuario**: El propietario del archivo o directorio.

2. **Grupo**: el grupo de usuarios propietario del archivo o directorio.

3. **Otros**: Otros usuarios que no son propietarios del archivo ni pertenecen al grupo propietario del archivo.

Para establecer estos permisos, Linux utiliza un sistema de bits de permiso. Esta información se puede ver y manipular mediante comandos como `chmod`, `chown` y `chgrp`.

```bash
chmod 755 my_file
chown new_owner my_file
chgrp new_group my_file
```

En el ejemplo anterior, `chmod 755 my_file` establece permisos para que el usuario pueda leer, escribir y ejecutar (7), mientras que el grupo y otros pueden leer y ejecutar (5). Los comandos `chown` y `chgrp` cambian el propietario y el grupo de `my_file`, respectivamente.