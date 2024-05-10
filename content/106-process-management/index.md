# Gestión de proceso

La gestión de procesos es parte integral de cualquier sistema operativo y Linux no es diferente. Cada programa que se ejecuta en Linux, ya sea una aplicación o una operación del sistema, se trata como un proceso. Estos procesos realizan diferentes tareas pero trabajan juntos para brindar una experiencia operativa perfecta.

En Linux, los usuarios pueden interactuar y administrar estos procesos mediante el uso de diferentes comandos para diversas tareas de administración de procesos, como ver los procesos actualmente en ejecución, finalizar procesos, cambiar la prioridad de un proceso, etc. Comprender estos comandos y cómo utilizarlos de forma eficaz es esencial para la gestión de procesos de Linux.

El comando `ps`, por ejemplo, proporciona información sobre los procesos actualmente en ejecución:

```bash
ps aux
```

Esto enumerará todos los procesos actualmente en ejecución con información como el ID del proceso, el usuario que ejecuta ese proceso, la CPU y la memoria que consume, el comando que inició el proceso y más.

`top` es otro comando común. Proporciona una vista actualizada y en vivo del estado actual del sistema, incluidos los procesos:

```bash
top
```

Otra herramienta poderosa es "kill", que puede enviar señales específicas a los procesos. Por ejemplo, puedes detener un proceso con gracia con `SIGTERM` (15) o detener uno a la fuerza con `SIGKILL` (9):

```bash
kill -SIGTERM pid
kill -SIGKILL pid
```

(nota: reemplaza `pid` con el ID del proceso que desea detener)