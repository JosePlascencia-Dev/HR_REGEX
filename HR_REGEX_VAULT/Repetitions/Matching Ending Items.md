## Problema:

> Write a RegEx to match a test string, ***S*** , under the following conditions:
> - ***S*** should consist of only lowercase and uppercase letters (no numbers or symbols).
> - ***S*** should end in `s`.
## Solución: Solución propia. 
### Cadena de la solución
```
"^[a-zA-Z]*s$"
``` 
### Explicación de la respuesta

Explicación de como se cumple cada requerimiento:
- Debe empezar "^" solo letras (mayúsculas o minúsculas) \[a-zA-Z].
- Debe terminar "$" con la letra "s".