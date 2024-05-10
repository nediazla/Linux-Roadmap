# Servicios en ejecución

Los servidores Linux son populares por su estabilidad y flexibilidad, factores que los convierten en la opción preferida de empresas y organizaciones cuando se trata de administrar diversos servicios. Los servicios que se ejecutan en un servidor Linux pueden variar desde servicios web hasta servicios de bases de datos, servidores DNS, servidores de correo y muchos otros.

Como administrador de un sistema Linux, es importante revisar periódicamente estos servicios en ejecución para administrar los recursos, verificar sus estados y solucionar problemas, garantizando la salud y el rendimiento del servidor.

Linux tiene una variedad de herramientas para lograr esto, como: `systemctl`, `service`, `netstat`, `ss` y `lsof`.

Por ejemplo, el comando `systemctl` se usa ampliamente en sistemas Linux para enumerar todos los servicios en ejecución:

```bash
systemctl --type=service 
```

Este comando mostrará una lista de todos los servicios activos junto con su estado actual. Es una necesidad para la gestión de servidores y debería formar parte de la caja de herramientas de cualquier administrador de sistemas Linux.