## Problema:

> Write a RegEx that will match a string satisfying the following conditions:
> 
> - The string's length is \>=5
> - The first character must be a lowercase English alphabetic character.
> - The second character must be a _positive_ digit. Note that we consider zero to be neither positive nor negative.
> - The third character must _not_ be a lowercase English alphabetic character.
> - The fourth character must _not_ be an uppercase English alphabetic character.
> - The fifth character must be an uppercase English alphabetic character.
## Solución: Solucion propia.
### Cadena de la solución
```
"^[a-z][1-9][^a-z][^A-Z][A-Z]"
``` 
### Explicación de la respuesta

Explicación de como se cumple cada requerimiento:
-  `^[a-z]` El primer carácter "^" debe ser una letra minúscula.
- `[1-9]` El segundo carácter debe ser un numero positivo.
- `[^a-z]`  El tercer carácter no debe ser una letra minúscula.
- `[^A-Z]` El cuarto carácter no debe se una letra mayúscula.
- `[A-Z]` El quinto carácter debe ser una letra mayúscula.