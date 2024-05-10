# Creando archivos

Linux ofrece una interfaz de línea de comandos (CLI) versátil y potente que ayuda a los usuarios a realizar diversas tareas, como la creación y navegación de archivos. Aprender a crear archivos es una de las habilidades fundamentales para los novatos que se aventuran en el mundo Linux. Una de las formas más sencillas de crear un archivo en Linux es con el comando `touch`. Este comando, cuando se le proporciona el nombre de un archivo como parámetro, crea un nuevo archivo con el nombre dado o, si ya existe un archivo con ese nombre, actualiza la última hora de modificación del archivo.

Otro comando útil para crear archivos es `cat >nombrearchivo`. Este comando crea un nuevo fichero con el nombre especificado y espera la entrada del usuario. Por lo tanto, el proceso termina cuando se pulsa `Ctrl+D` para enviar `EOF` (End-Of-File) al comando `cat`.

He aquí un ejemplo de creación de ficheros con el comando `touch`:

```bash
touch newfile.txt
```

y con el comando `cat`:

```bash
cat > newfile.txt
```

Ambos comandos crean un nuevo «newfile.txt» si no existe ya.

[Anterior](101-moving-files) - [Siguiente](103-directory-hierarchy)