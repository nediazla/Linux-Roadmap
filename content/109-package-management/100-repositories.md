# Repositorios

La gestión de paquetes en Linux implica manejar paquetes o módulos de software, agilizando el proceso de instalación, actualización y configuración de distribuciones de Linux. En el centro de la gestión de paquetes se encuentran los repositorios, componentes críticos que almacenan y gestionan colecciones de paquetes de software.

Un repositorio en Linux es una ubicación de almacenamiento desde donde el sistema recupera e instala las actualizaciones y aplicaciones necesarias del sistema operativo. Estos repositorios contienen miles de paquetes de software o paquetes RPM compilados para distribuciones de Linux específicas.

El repositorio específico utilizado depende de la distribución de Linux (como Ubuntu, Fedora, etc.) y del formato de paquete que utiliza la distribución (como `.deb` en Debian y Ubuntu o `.rpm` en Fedora y CentOS).

Los repositorios proporcionan un método para actualizar las herramientas y aplicaciones en su sistema Linux y también garantizan que todas las actualizaciones y dependencias funcionen juntas y se prueben para su integración antes de su lanzamiento.

No existe una forma estándar de utilizar los repositorios en varias distribuciones, cada una viene con su conjunto de repositorios preconfigurados.

```
sudo apt update      # command to update the repository in Ubuntu
sudo yum update      # command to update the repository in CentOS or Fedora
raco pkg update      # command in Racket to update all installed packages
```

Estos repositorios son los que hacen de Linux una fuerza a tener en cuenta cuando se trata de gestión de software con un elemento de seguridad que garantiza que los usuarios sólo instalen software que sea seguro y confiable.