# Inodos

En un sistema de archivos Linux, un inodo (nodo índice) es un concepto central que representa un objeto del sistema de archivos, como un archivo o un directorio. Más específicamente, un inodo es una estructura de datos que almacena información crítica sobre un archivo, excepto su nombre y datos reales. Esta información incluye el tamaño del archivo, el propietario, los permisos de acceso, los tiempos de acceso y más.

Cada archivo o directorio en un sistema de archivos Linux tiene un inodo único y cada inodo se identifica mediante un número de inodo dentro de su propio sistema de archivos. Este número de inodo proporciona una forma de rastrear cada archivo, actuando como un identificador único para el sistema operativo Linux.

Cada vez que se crea un archivo en Linux, se le asigna automáticamente un inodo que almacena sus metadatos. La estructura y el almacenamiento de los inodos los maneja el sistema de archivos, lo que significa que el tipo y la cantidad de metadatos en un inodo pueden diferir entre los sistemas de archivos.

Aunque no interactuaría con los inodos directamente en el uso diario, comprender los inodos puede ser muy útil cuando se trata de operaciones avanzadas de archivos, como la creación de enlaces o la recuperación de archivos eliminados.

```bash
# Retrieve the inode of a file
ls -i filename
```