# Variables de entorno en Shell Básico

En Linux, las variables de entorno son valores dinámicos con nombre que pueden afectar al comportamiento de los procesos que se ejecutan en un shell. Existen en cada sesión de shell. El entorno de una sesión de shell incluye, entre otros, el directorio personal del usuario, la ruta de búsqueda de comandos, el tipo de terminal y las preferencias de programa. 

Las variables de entorno contribuyen a la fantástica y personalizable flexibilidad que se ve en los sistemas Unix. Proporcionan una forma sencilla de compartir ajustes de configuración entre múltiples aplicaciones y procesos en Linux.

Puedes utilizar el comando 'env' para listar todas las variables de entorno en una sesión de shell. Si quieres imprimir una variable en particular, como la variable PATH, puedes usar el comando 'echo $PATH'.

He aquí un ejemplo de cómo hacerlo:

```bash
# Listar todas las variables de entorno
$env

# Imprime una variable en particular como PATH
$ echo $PATH
```

Recuerda, cada shell, como Bourne shell, C shell, o Korn shell en Unix o Linux tiene diferente sintaxis y semántica para definir y usar variables de entorno.