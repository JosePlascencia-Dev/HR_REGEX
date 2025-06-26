## Problema:

> You have a test string ***S***.  
> Your task is to write a regex that will match ***S*** using the following conditions:
> - ***S*** must be of length equal to **`45`**.
> - The first `40` characters should consist of letters(both lowercase and uppercase), or of even digits.
> - The last `5` characters should consist of **`odd digits`** or **`whitespace characters`**.
## Solución: Solución propia.
### Cadena de la solución
```
"^([a-zA-z]|[24680]){40}([13579]|\s){5}$"
``` 
### Explicación de la respuesta

Explicación de como se cumple cada requerimiento:
- Los primeros "^" 40 caracteres "{40}" deben ser letras mayúsculas y minúsculas o números pares "\[a-zA-z]|\[24680\]".
- Los últimos "$" cinco "{5}" caracteres deben ser números impares o espacios en blanco