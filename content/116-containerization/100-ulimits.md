# Entendiendo los límites U

La tecnología de contenedorización basada en Linux, como Docker, utiliza 'ulimits' como una de las características de seguridad para controlar el consumo de recursos de cada contenedor en ejecución. Los ulimits (límites de usuario) son una característica del kernel de Linux que restringe los recursos que puede consumir cualquier usuario. Estos recursos incluyen identificadores de archivos abiertos, memoria física bloqueada y otros.

Usados de manera efectiva, ulimits pueden evitar que un proceso malicioso o errante en un contenedor en particular agote los recursos del servidor y cree una situación de denegación de servicio para otros contenedores o procesos.

En un entorno de contenedores, es fundamental gestionar hábilmente estos límites de recursos para garantizar el rendimiento y la seguridad óptimos de todos los contenedores.

```bash
# To see current ulimits:
ulimit -a

# To set a specific ulimit (soft limit), for example file handles:
ulimit -n 1024
```

Configurar y comprender correctamente "ulimits", especialmente en entornos en contenedores, es una parte esencial de la administración del sistema en Linux.