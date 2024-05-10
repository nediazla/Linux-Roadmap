# Enrutamiento IP

El enrutamiento IP en Linux se refiere al proceso de configurar tablas de enrutamiento y rutas de red para interfaces de red dentro del sistema operativo Linux. Es responsabilidad del núcleo manejar esta tarea que implica la selección de rutas para enviar paquetes de red a sus destinos previstos en una red.

Esta tarea se lleva a cabo utilizando varias herramientas de línea de comandos y archivos de configuración de red. La principal herramienta de línea de comandos para la configuración de red en Linux solía ser `ifconfig`, pero ahora ha sido reemplazada en su mayor parte por el comando `ip`.

Por ejemplo, para ver la tabla de enrutamiento en Linux, se utiliza el siguiente comando:

```bash
$ ip route show
```

Este comando devuelve una lista de todas las rutas conocidas por el kernel.