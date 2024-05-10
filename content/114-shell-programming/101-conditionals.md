# Condicionales

Las declaraciones condicionales en la programación de Shell de Linux permiten que los scripts tomen decisiones basadas en condiciones. Son parte integral de cualquier lenguaje de programación y, al igual que otros lenguajes como C, Python, JavaScript, Linux Shell también proporciona declaraciones condicionales. Una declaración condicional se puede definir como una parte integral del script de shell que guía al intérprete hacia la ruta correcta de ejecución dependiendo de las condiciones dadas.

En Shell, los comandos principales que se utilizan para declaraciones condicionales son `if`, `elif` (si no) y `else`. Estos comandos se utilizan para el control de procesos en función de los resultados de pruebas condicionales que pueden evaluar el valor de variables de cadena, pruebas aritméticas o el estado de un proceso.

A continuación se muestra una ilustración sencilla de cómo funcionan:

```bash
#!/bin/sh
a=10
b=20

if [ $a -lt 20 ]
then
   echo "a is less than b"
elif [ $a -gt 20 ]
then
   echo "a is greater than b"
else
   echo "a is equal to b"
fi
```

En el script anterior, se verifica la condición dentro de la declaración `if`. Si la condición es `verdadera`, entonces el bloque de código dentro de la declaración `if` se ejecuta; de lo contrario, pasa a la condición `elif` y así sucesivamente. Si no se cumple ninguna de esas condiciones, se ejecutará el bloque de código dentro de la declaración `else`.