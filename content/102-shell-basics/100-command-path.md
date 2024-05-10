# Ruta de comandos en conceptos básicos de Shell

En Linux, la ruta de comandos es un concepto importante en los fundamentos del shell. En pocas palabras, la ruta de comandos es una variable que es utilizada por el shell para determinar dónde buscar los archivos ejecutables a ejecutar. Los comandos de Linux no son más que programas que residen en directorios particulares. Pero, uno no tiene que navegar a estos directorios cada vez para ejecutar estos programas. ¡La ruta de comandos viene al rescate!

Normalmente, cuando escribes un comando en el terminal, el shell necesita saber la ruta absoluta del ejecutable del comando para ejecutarlo. En lugar de escribir la ruta completa cada vez, las rutas de comandos permiten al shell buscar automáticamente en los directorios indicados en el orden correcto. Estas rutas se almacenan en la variable de entorno $PATH. 

```sh
echo $PATH
```
Ejecutando este comando en un terminal Linux se devolverán todos los directorios que el shell buscará, en orden, para encontrar el comando que tiene que ejecutar. Los directorios están separados por dos puntos.

Esta característica hace que el uso de la interfaz de línea de comandos de Linux sea cómodo y eficiente.