# Resolución DNS en Redes en Linux

El sistema de nombres de dominio (DNS) es un sistema descentralizado que se utiliza para convertir nombres de host en direcciones IP, lo que facilita a los usuarios el acceso a sitios web sin tener que recordar direcciones IP numéricas específicas. Por lo tanto, la resolución DNS es un aspecto crítico de las redes en Linux.

En los sistemas Linux, cuando una aplicación necesita conectarse a una determinada URL, consulta el solucionador de DNS. Este solucionador, utilizando el archivo `/etc/resolv.conf`, se comunica con el servidor DNS, que luego convierte la URL en una dirección IP para establecer una conexión de red.

El siguiente comando se utiliza para consultar DNS y obtener direcciones IP:

```bash
nslookup www.example.com
```

O usando el comando dig:

```bash
dig www.example.com
```

Comprender bien el proceso de resolución de DNS proporciona una base sólida para tareas como la resolución de problemas de red y la configuración del servidor web en un sistema Linux.