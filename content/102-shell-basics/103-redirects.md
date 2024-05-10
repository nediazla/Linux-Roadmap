# Redirecciones en Shell Básico

El shell en Linux proporciona una forma robusta de gestionar los flujos de entrada y salida de un comando o programa, este mecanismo se conoce como Redirección. Linux es un sistema operativo multiusuario y multitarea, cada proceso normalmente tiene 3 flujos abiertos:

- Entrada estándar (stdin) - Es de donde el proceso lee su entrada. Por defecto es el teclado.
- Salida estándar (stdout) - El proceso escribe su salida en stdout. Por defecto, esto significa la terminal.
- Error estándar (stderr) - El proceso escribe mensajes de error en stderr. Por defecto, esto también va a la terminal.

La redirección en Linux nos permite manipular estos flujos, avanzando en la flexibilidad con la que se ejecutan los comandos o programas. Además de los dispositivos por defecto (teclado para entrada y terminal para salida), los flujos de E/S pueden ser redirigidos a ficheros u otros dispositivos.

Por ejemplo, si queremos almacenar la salida de un comando en un fichero en lugar de imprimirla en la consola, podemos utilizar el operador `>`.

```bash
ls -al > file_list.txt
```

Este comando escribirá la salida de `ls -al` en `file_list.txt`, exista o no el fichero inicialmente. Se creará si es necesario, y si ya existe - se sobrescribirá.
