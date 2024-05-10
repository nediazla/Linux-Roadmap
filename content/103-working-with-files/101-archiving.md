# Archivo

Linux ofrece potentes utilidades para el archivado, donde múltiples ficheros y directorios se combinan en un único fichero, principalmente para realizar copias de seguridad y simplificar la distribución. Las principales herramientas utilizadas para este fin son `tar`, `gzip` y `bzip2`. 

El comando `tar`, originalmente para archivar cintas, es una herramienta versátil que puede gestionar y organizar ficheros en un solo archivo. Por su parte, `gzip` y `bzip2` se utilizan para comprimir archivos, reducir su tamaño y facilitar la transmisión de datos.

Echa un vistazo a los siguientes comandos en uso:

```bash
# To create a tar archive:
tar cvf archive_name.tar directory_to_archive/

# To extract a tar archive:
tar xvf archive_name.tar

# To create a gzip compressed tar archive:
tar cvzf archive_name.tar.gz directory_to_archive/

#To create a bzip2 compressed tar archive:
tar cvjf archive_name.tar.bz2 directory_to_archive/
```

Recuerda, en Linux, archivar y comprimir son procesos separados, de ahí `tar` para archivar y `gzip`/`bzip2` para comprimir. Aunque normalmente se usan juntos, pueden usarse por separado según las necesidades.
