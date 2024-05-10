# Prioridades de proceso bajo gestión de procesos

En el entorno Linux, a cada tarea en ejecución o esencialmente a un "proceso" se le asigna un cierto nivel de prioridad que afecta su tiempo de ejecución. Estas prioridades son fundamentales para la utilización eficiente de los recursos del sistema, lo que permite a Linux ajustar la ejecución y asignar los recursos del sistema de manera inteligente.

El kernel de Linux clasifica los procesos en la estructura proc, que normalmente se encuentra en el directorio del sistema de archivos `/proc`. Esta estructura contiene información sobre todos los procesos activos, incluidas sus prioridades. El concepto de prioridades de proceso en la gestión de procesos se refiere a la prioridad que el sistema otorga a cada proceso. Este valor de prioridad (también conocido como "nice") oscila entre -20 (prioridad más alta) y +19 (prioridad más baja).

Al comprender y administrar las prioridades de los procesos, puede optimizar el rendimiento del sistema y controlar qué procesos reciben más o menos atención de la CPU.

Aquí hay un comando simple en la terminal de Linux para mostrar el ID del proceso, la prioridad y el usuario de todos los procesos:

```sh
ps -eo pid,pri,user
``` 

Para cambiar la prioridad de cualquier proceso, puede usar el comando `renice`:

```sh
renice +5 -p [PID]   # Increase priority by 5 units for process ID [PID]
```