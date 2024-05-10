# Gestión de usuarios

El sistema operativo Linux ofrece un sistema de gestión de usuarios estructurado, que permite que varios usuarios interactúen con el mismo sistema de forma aislada. Esto incluye definir roles de usuario, asignar permisos, grupos, propiedad y otros aspectos relacionados, que son tareas cruciales para los administradores de Linux.

Para un funcionamiento más fluido y controlado, la gestión de usuarios en Linux incluye tareas como crear, eliminar y modificar usuarios y grupos. También implica asignar permisos y propiedad de archivos y directorios a usuarios/grupos.

Los comandos básicos de shell son una parte fundamental de la gestión de usuarios en Linux. Por ejemplo, `adduser` o `useradd` se utilizan para crear un nuevo usuario en un sistema:

```bash
sudo adduser newuser
```

De manera similar, `deluser` o `userdel` se utilizan para eliminar un usuario:

```bash
sudo deluser newuser
```

Todo el concepto de gestión de usuarios gira en torno a proporcionar una accesibilidad adecuada y mantener la seguridad del sistema operativo Linux. Otros comandos como `passwd` para administrar contraseñas o `su` para cambiar de usuario enfatizan aún más la profundidad y la importancia de la administración de usuarios en Linux.