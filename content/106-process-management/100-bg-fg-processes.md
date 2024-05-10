# Gestión de procesos bg (fondo) y fg (primer plano)

En el entorno Linux, un proceso se puede ejecutar en primer plano (fg) o en segundo plano (bg). El proceso en primer plano recibe información directamente del usuario y muestra resultados y errores en el terminal del usuario. Por otro lado, se ejecuta un proceso en segundo plano independientemente de las acciones del usuario, liberando el terminal para otras tareas.

Normalmente, un proceso comienza en primer plano. Sin embargo, puede enviarlo a segundo plano agregando un signo comercial (&) al comando o usando el comando `bg`. Por el contrario, el comando `fg` trae un proceso en segundo plano al primer plano.

Así es como puedes enviar un proceso en ejecución a segundo plano:

```bash
command &
```

O si ya hay un proceso en ejecución:

```bash
CTRL + Z       # This will pause the process
bg             # This resumes the paused process in the background
```

Y para volver a ponerlo en primer plano:

```bash
fg
``` 

Estos comandos, `bg` y `fg`, son parte del control de trabajos en sistemas operativos tipo Unix, que le permiten administrar múltiples tareas simultáneamente desde una sola terminal.