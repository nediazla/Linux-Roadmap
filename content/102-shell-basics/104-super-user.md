# Super Usuario

El Super Usuario, también conocido como «usuario root», representa una cuenta de usuario en Linux con amplios poderes, privilegios y capacidades. Este usuario tiene control total sobre el sistema y puede acceder a cualquier dato almacenado en él. Esto incluye la capacidad de modificar las configuraciones del sistema, cambiar las contraseñas de otros usuarios, instalar software y realizar más tareas administrativas en el entorno shell.

El uso del superusuario es crítico para operar un sistema Linux de forma adecuada y segura, ya que puede potencialmente causar serios daños. Se puede acceder al superusuario a través de los comandos `sudo` o `su`.

En concreto, `su` cambia el usuario actual a root, mientras que `sudo` permite ejecutar un comando como otro usuario, siendo por defecto root. Sin embargo, también tienen una diferencia clave y es que `sudo` registrará los comandos y sus argumentos, lo que puede ser una pista de auditoría muy útil.

```bash
# This would prompt for root password and switch you to root usermode
$ su -

# To perform a command as superuser (if allowed in sudoers list)
$ sudo <command>
```

Tenga en cuenta que los privilegios de superusuario deben manejarse con cuidado debido a su potencial para alterar la funcionalidad del sistema. Los cambios erróneos en archivos clave del sistema o el acceso no autorizado pueden provocar problemas graves.