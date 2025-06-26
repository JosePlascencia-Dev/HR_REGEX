## Problema:

> You have a test string ***S***.  
> Your task is to write a regex that will match ***S*** with following conditions:
> - ***S*** must be of length: **`6`**
> - First character: **`1`**, **`2`** or **`3`**
> - Second character: **`1`**, **`2`** or **`0`**
> - Third character: **`x`**, **`s`** or **`0`**
> - Fourth character: **`3`**, **`0`** , **`A`** or **`a`**
> - Fifth character: **`x`**, **`s`** or **`u`**
> - Sixth character: **`.`** or **`,`**
## Solución: Solución propia. 
### Cadena de la solución

```
"^[123][120][xs0][30Aa][xsu][\.,]$"
``` 
### Explicación de la respuesta

Utilice "\["  "\]" porque simboliza un conjunto de caracteres, lo único que se hizo fue poner los caracteres permitidos en cada espacio, con restricciones para el inicio y el fin de la cadena
