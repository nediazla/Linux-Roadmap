# Contenedorización

La contenedorización es un método de virtualización que implica encapsular una aplicación en un contenedor con su propio entorno operativo aislado. Este método avanzado permite que las aplicaciones se ejecuten de manera confiable y rápida cuando se mueven de un entorno informático a otro. En Linux, esta tecnología se puede utilizar utilizando varias plataformas de código abierto como Docker y Kubernetes.

Los contenedores a menudo se comparan con máquinas virtuales (VM). Sin embargo, a diferencia de las máquinas virtuales que necesitan un sistema operativo completo para ejecutar una aplicación, un contenedor comparte el espacio de usuario del sistema host. Por eso son ligeros y más rápidos.

En Linux, Docker es una herramienta popular que se utiliza para la contenedorización. A continuación se muestra un ejemplo básico de cómo ejecutaría un contenedor en Docker:

```bash
docker run -it ubuntu bash
```

Este comando extrae la imagen de Ubuntu de Docker Hub y la ejecuta como un contenedor en su sistema, proporcionándole una terminal interactiva (`-it`) dentro del contenedor. Este es solo un caso de uso simple y Docker se puede usar para administrar aplicaciones complejas que involucran muchos contenedores.