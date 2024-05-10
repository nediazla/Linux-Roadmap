# Listado de paquetes instalados

Linux, conocido por su robustez y flexibilidad, proporciona varios administradores de paquetes que ayudan en la gestión del software. Estos administradores de paquetes nos ayudan a instalar, actualizar o eliminar software de forma sistemática. Cada distribución de Linux puede venir con su propio sistema de gestión de paquetes. Los ejemplos incluyen `apt` en sistemas basados en Debian, `dnf` en Fedora, `zypper` en OpenSUSE y `pacman` en Arch Linux.

Una tarea común que puede necesitar con frecuencia es enumerar los paquetes instalados en su sistema. Esta tarea puede ayudar en varios escenarios, como auditar el software instalado, crear secuencias de comandos o automatizar la implementación de software en máquinas nuevas.

A continuación se muestra el comando para enumerar los paquetes instalados en un administrador de paquetes `apt`:

```shell
sudo apt list --installed
```

Para el administrador de paquetes `dnf`, usaría:

```shell
dnf list installed
```

Recuerde, las diferentes distribuciones tendrán su propia sintaxis para este comando.