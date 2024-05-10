# Traceroute 

Traceroute es una herramienta de diagnóstico de red que se utiliza ampliamente en sistemas Linux para solucionar problemas. Está diseñado para mostrar la ruta que toman los paquetes desde el sistema donde se ejecuta traceroute hasta un sistema o sitio web de destino específico. Se utiliza para identificar problemas de enrutamiento, ofrecer medición de latencia y determinar la estructura de la red a medida que los paquetes viajan a través de Internet.

Cada salto a lo largo de la ruta se prueba varias veces (el valor predeterminado es 3, pero se puede cambiar) y se muestra el tiempo de ida y vuelta para cada paquete. Si ciertos paquetes no logran llegar a su destino, traceroute puede ayudar a diagnosticar dónde se produce la falla.

El seguimiento de rutas en Linux se puede lograr ejecutando el comando `traceroute` que le permite descubrir las rutas que siguen los paquetes de protocolo de Internet cuando viajan a su destino.

```bash
$ traceroute www.example.com
```