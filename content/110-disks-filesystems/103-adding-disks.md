# Agregar discos

En Linux, los discos duros y las unidades portátiles se administran y controlan a través de una serie de directorios y archivos, comúnmente conocidos como sistema de archivos de Linux. Cuando agrega nuevos discos en Linux, debe prepararlos antes de poder usarlos.

El proceso implica crear particiones en el disco, crear un sistema de archivos en las particiones y luego montar los sistemas de archivos en directorios en el árbol de directorios de su sistema. Esto resulta importante especialmente cuando se trabaja con varias unidades de disco o grandes unidades de almacenamiento de datos para crear una experiencia de usuario perfecta.

Los siguientes son comandos comunes para administrar discos:

- Utilice `lsblk` para enumerar todos los dispositivos de bloque (disco y particiones).
- Utilice `fdisk /dev/sdX` para crear una nueva partición en un disco.
- Utilice `mkfs.ext4 /dev/sdX1` para crear un nuevo sistema de archivos en una partición.
- Utilice `mount /dev/sdX1 /mount/point` para montar un sistema de archivos en un directorio.

```shell
# example commands to add new disk
lsblk                     # list all disks and partitions
sudo fdisk /dev/sdb       # let's suppose new disk is /dev/sdb
sudo mkfs.ext4 /dev/sdb1  # make filesystem(e.g., ext4) on partition 1
sudo mount /dev/sdb1 /mnt # mount new filesystem to /mnt directory
``` 

Recuerde reemplazar `/dev/sdb` y `/dev/sdb1` con sus identificadores de disco y partición reales. El punto de montaje `/mnt` también se puede reemplazar con cualquier otro directorio según la estructura y preferencia de su sistema.