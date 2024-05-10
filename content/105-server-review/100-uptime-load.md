# Carga de tiempo de actividad - uptime

Cuando se gestiona un servidor Linux, una métrica crítica que merece un escrutinio minucioso es el «tiempo de actividad». El comando `uptime` en Linux da información sobre cuánto tiempo ha estado funcionando el sistema sin apagarse o reiniciarse, y el promedio de carga del sistema.

El promedio de carga del sistema es un indicador importante que ilustra la cantidad de trabajo computacional que realiza un sistema informático. Es un reflejo de cuántos procesos están esperando en línea para obtener tiempo de CPU. El promedio de carga del sistema se muestra normalmente para duraciones de 1, 5 y 15 minutos.

Analizando constantemente el tiempo de actividad y la carga de un servidor Linux, los administradores pueden identificar patrones de uso del sistema, diagnosticar posibles problemas de rendimiento y determinar una estrategia eficiente de planificación de la capacidad. Si un servidor tiene una media de carga alta, puede sugerir que los recursos del sistema no son suficientes o están mal configurados, lo que puede provocar un rendimiento lento o que el sistema no responda. 

A continuación se muestra un ejemplo del comando `uptime` y su salida:

```bash
$ uptime
 10:58:35 up 2 days, 20 min,  1 user,  load average: 0.00, 0.01, 0.05
```

En la salida anterior, «2 días, 20 minutos» nos indica el tiempo que lleva funcionando el sistema, mientras que «0,00, 0,01, 0,05» muestra la media de carga del sistema en los últimos uno, cinco y quince minutos, respectivamente.