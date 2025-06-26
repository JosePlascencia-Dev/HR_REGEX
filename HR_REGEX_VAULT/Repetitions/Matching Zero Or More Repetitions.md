## Problema:

> You have a test string ***S*** .  
> Your task is to write a regex that will match ***S*** using the following conditions:
> - ***S*** should begin with `2` or more **digits**.
> - After that, ***S*** should have `0` or more **`lowercase letters`**.
> - ***S*** should end with `0` or more uppercase letters.
## Solución: Solución propia.
### Cadena de la solución
```
"^\d{2,}[a-z]*[A-Z]*$"
``` 
### Explicación de la respuesta

Explicación de como se cumple cada requerimiento:
- Debe empezar "^" con 2 o mas "{2,}" dígitos "\d".
- Debe de tener 0 o mas "\*"  letras minúsculas "\[a-z]".
- Debe terminar "$" con 0 o mas letras mayusculas "\[A-Z]".
