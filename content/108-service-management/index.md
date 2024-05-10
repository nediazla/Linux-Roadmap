# Gestión De Servicios

La gestión de servicios en Linux se refiere al sistema de control de los servicios (o "demonios") que Linux inicia y detiene durante el proceso de inicio y apagado de su computadora. Estos servicios realizan varias funciones y proporcionan procesos que no están adjuntos a la interfaz de usuario.

Los sistemas Linux, particularmente los administradores de sistemas, a menudo necesitan administrar estos servicios, como iniciarlos o detenerlos, habilitarlos o deshabilitarlos en el momento del arranque, etc. Varios comandos involucrados en la administración de servicios en Linux incluyen `systemctl start`, `systemctl stop`, `systemctl restart`, `systemctl reload`, `systemctl status` y `systemctl enable/disable`, entre otros.

En las distribuciones modernas de Linux, la gestión de servicios la maneja principalmente `systemd`, pero en distribuciones más antiguas o minimalistas, la manejan sistemas más antiguos como `SystemV` o `Upstart`.

A continuación se muestra un ejemplo básico de cómo iniciar y verificar el estado de un servicio (por ejemplo, servicio `sshd`) usando `systemctl`:

```bash
# Start sshd service
sudo systemctl start sshd

# Check status of sshd service
sudo systemctl status sshd
```

La gestión de servicios es una habilidad clave en la administración de sistemas Linux y esencial para mantener un sistema seguro y estable.