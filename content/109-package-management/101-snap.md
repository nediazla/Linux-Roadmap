# Snap

Snap es un enfoque moderno para la gestión de paquetes en sistemas Linux promovido por Canonical (la empresa detrás de Ubuntu). A diferencia de los sistemas tradicionales de administración de paquetes como dpkg o RPM, Snap se enfoca en proporcionar software como paquetes autónomos (conocidos como `Snaps`) que incluyen todas sus dependencias. Esto garantiza que una aplicación Snap se ejecute de manera consistente en una variedad de distribuciones de Linux diferentes.

Las instantáneas se instalan desde una tienda Snapcraft y se actualizan automáticamente en segundo plano. El proceso de actualización de Snap es transaccional, lo que significa que si algo sale mal durante una actualización, Snap puede volver automáticamente a la versión anterior.

A continuación se muestra un ejemplo sencillo de un comando de ajuste:

```sh
sudo snap install [package-name]
```

En el comando anterior, `[nombre-paquete]` es el nombre del paquete instantáneo que desea instalar. Debe ejecutar este comando como superusuario (sudo), ya que se necesitan privilegios de root para instalar paquetes.
