# Netstat 

Netstat, abreviatura de estadísticas de red, es una herramienta de línea de comandos incorporada que se utiliza en sistemas Linux para solucionar problemas de red y medir el rendimiento. Proporciona estadísticas de protocolos, una lista de puertos abiertos, información de la tabla de enrutamiento y otros detalles importantes de la red. Los administradores y desarrolladores trabajan con netstat para examinar problemas de red y comprender cómo se comunica un sistema con otros.

Su funcionalidad se amplía debido a varias opciones de línea de comandos que admite, que podrían usarse de forma individual o combinada para ajustar la salida. Estos podrían incluir mostrar direcciones numéricas en lugar de nombres (`-n`), monitoreo continuo (`-c`) o detectar conexiones en un protocolo específico (`-t`, `-u`).

Aquí hay un breve fragmento de cómo se puede usar normalmente netstat:

```bash
# List all connections with numerical values.
netstat -n
```