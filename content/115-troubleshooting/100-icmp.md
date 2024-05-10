# ICMP

El Protocolo de mensajes de control de Internet (ICMP) es un protocolo de soporte utilizado principalmente por dispositivos de red para comunicar actualizaciones o información de errores a otros dispositivos. Al solucionar problemas de red en un entorno Linux, ICMP constituye un aspecto crucial. Puede utilizarse para enviar mensajes de error que indiquen, por ejemplo, que un servicio solicitado no está disponible o que no se pudo acceder a un host o enrutador. ICMP también se puede utilizar para transmitir mensajes de consulta.

En los sistemas Linux, las herramientas de línea de comandos comunes relacionadas con ICMP incluyen "ping" y "traceroute", ambas utilizadas para diagnosticar el estado de la red y, a menudo, parte de los esfuerzos de solución de problemas.

```bash
# Use of ICMP via the ping command to send an echo request to a specific host
ping www.google.com
```

Esta herramienta simple pero efectiva no debe faltar en ningún arsenal de solución de problemas de redes Linux.