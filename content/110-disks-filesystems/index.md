# Sistemas de archivos de discos Linux

Linux utiliza una variedad de sistemas de archivos que nos permiten almacenar y recuperar datos del hardware de un sistema informático, como los discos. El sistema de archivos define cómo se organizan, almacenan y recuperan los datos en estos dispositivos de almacenamiento. Ejemplos de sistemas de archivos Linux populares incluyen EXT4, FAT32, NTFS y Btrfs.

Cada sistema de archivos tiene sus propias ventajas, desventajas y casos de uso. Por ejemplo, EXT4 se usa normalmente para volúmenes de sistemas Linux debido a su solidez y compatibilidad con Linux, mientras que FAT32 se puede usar para medios extraíbles como unidades USB por su compatibilidad con casi todos los sistemas operativos.

Aquí hay un ejemplo de cómo mostrar el tipo de sistemas de archivos de sus dispositivos montados con el comando `df` en Linux:

```bash
df -T
```

El resultado muestra los nombres de sus discos, sus tipos de sistemas de archivos y otra información adicional, como el espacio total, el espacio utilizado y el espacio disponible en los discos.