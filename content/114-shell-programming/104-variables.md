# Variables

En el contexto de la programación Shell en Linux, una variable es una cadena de caracteres que puede almacenar datos del sistema o datos definidos por el usuario. Es un nombre simbólico que se asigna a una cantidad de espacio de almacenamiento que puede cambiar su valor durante la ejecución del programa. Las variables desempeñan un papel vital en cualquier paradigma de programación y los scripts de shell no son diferentes.

Las variables se dividen en dos categorías amplias: **Variables del sistema** y **Variables definidas por el usuario**. Las variables del sistema son creadas y mantenidas por el propio sistema Linux. Los ejemplos incluyen RUTA, INICIO y PWD. Las variables definidas por el usuario, por otro lado, son creadas y controladas por el usuario.

Una variable en las secuencias de comandos de shell se define mediante el operador '=" (igual) y el valor se puede recuperar anteponiendo al nombre de la variable un signo '$' (dólar).

```bash
# Create a User-Defined Variable
MY_VARIABLE="Hello World"

# Print the value of the Variable
echo $MY_VARIABLE  # Output: Hello World
```