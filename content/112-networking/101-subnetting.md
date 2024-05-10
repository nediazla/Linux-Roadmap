# Subnetting 

La creación de subredes es un proceso crítico en las redes Linux. Esta práctica implica dividir una red en dos o más redes, conocidas como subredes. La creación de subredes ayuda a mejorar el rendimiento y la seguridad de la red. En Linux, la división en subredes se puede administrar dentro del contexto del esquema de direccionamiento del Protocolo de Internet (IP), donde es crucial para organizar y administrar direcciones IP dentro de una red, prevenir conflictos de IP y utilizar rangos de direcciones IP de manera eficiente. Esta técnica es invaluable en entornos de redes Linux grandes y complejos donde la administración de direcciones IP puede volverse abrumadoramente compleja.

Generalmente, los siguientes comandos se utilizan en Linux para crear subredes:

```shell
# Display current routing table
$ route -n 

# Add a new subnet
$ route add -net xxx.xxx.xxx.x/xx gw yyy.yyy.yyy.y
```

Reemplace `xxx.xxx.xxx.x/xx` con la dirección de subred y máscara de red que desee y reemplace `yyy.yyy.yyy.y` con la puerta de enlace predeterminada prevista para la subred.