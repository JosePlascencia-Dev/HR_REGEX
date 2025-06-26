## Problema:

> You have a test string ***S***.  
> Your task is to write a regex that will match ***S*** with the following conditions: 
> - ***S*** must be of length **6**.
> - First character should **_not_** be a **digit** (1, 2, 3, 4, 5, 6, 7, 8, 9 or 0 ).
> - Second character should **_not_** be a **lowercase vowel** ( a, e, i, o or u).
> - Third character should _not_ be **b**, **c**, **D** or **F**.
> - Fourth character should _not_ be a **whitespace character** ( \r, \n, \t, \f or \<space\> ).
> - Fifth character should _not_ be a **uppercase vowel** (A, E, I, O or U ).
> - Sixth character should _not_ be a **`.`** or **`,`** symbol.

## Solución: Solucion Propia
### Cadena de la solución
```
"^[^\d][^aeiou][^bcDF][^\s][^AEIOU][^\.,]$"
``` 
### Explicación de la respuesta

Explicación de como se cumple cada requerimiento:
-  `"^[^\d]"` El primer carácter "^" no debe ser un dígito "\[^\d]".
- `[^aeiou]` El segundo carácter no debe ser una vocal.
- `[^bcDF]`  El tercer carácter no debe ser alguno de los caracteres que se mencionan.
- `[^\s]` El cuarto carácter no debe se un espacio en blanco.
- `[^AEIOU]` El quinto carácter no debe ser una vocal mayúscula.
- `[^\.,]$` El sexto carácter no debe ser un punto o una coma.