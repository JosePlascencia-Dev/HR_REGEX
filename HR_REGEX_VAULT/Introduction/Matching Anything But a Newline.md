## Problema:

> You have a test string ***S***.
> Your task is to write a regular expression that matches only and exactly strings of form: ***abc, def, ghi, jkx*** , where each variable ***a, b, c, d, f, g, h, i, j, k, x*** can be any single character except the newline.
## Solución: **Solución asistida**
### Cadena de la solución:

```
"^...\....\....\....$"
``` 
### Explicación de la respuesta

1. Carácter "***^***" : Representa el inicio de la cadena.
2. Carácter "***.***" : Depresenta **cualquier carácter** (letra, número, símbolo, espacio, etc.), excepto el salto de linea ("\n").
3. Secuencia "**\.**" : Dado que el metacaracter "." significa algo se coloca el carácter de escape "\" para que se reconozca como un el carácter "." y que en esa parte de la expresión va un punto. 
4. Caracter "$" : Representa el final de la cadena. 
## Uso y justificación de inteligencia artificial y otras fuentes.

No conozco lo suficiente de REGEX y debo admitir que no entendí correctamente el problema. y quería un ejemplo completo de como iría la documentación.
Utilice inteligencia artificial para entender el funcionamiento de la cadena que representa la solución, el prompt realizado fue únicamente:

```
"^...\....\....\....$"
```
## Fuentes.
https://www.codingbroz.com/hackerrank-regex-solutions/

https://www.deepseek.com/en