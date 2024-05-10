# Pipe

Pipe o La tubería (`|`) es una potente característica de Linux que se utiliza para conectar dos o más comandos entre sí. Este mecanismo permite «canalizar» la salida de un comando como entrada de otro. En lo que respecta al procesamiento de texto, el uso de tuberías es especialmente útil, ya que permite manipular, analizar y transformar datos de texto sin necesidad de crear archivos o programas intermedios.

He aquí un sencillo ejemplo de canalización de dos comandos, `ls` y `grep`, para listar todos los ficheros de texto del directorio actual:

```bash
ls | grep .txt
```

En este ejemplo, `ls` lista los ficheros del directorio actual y `grep .txt` filtra los ficheros que no terminan en `.txt`. El comando pipe, `|`, toma la salida de `ls` y la utiliza como entrada para `grep .txt`. La salida del comando completo es la lista de ficheros de texto en el directorio actual.