## Problema:

> You have a test string ***S***.  
> Your task is to write a regex that will match ***S*** using the following conditions:
> - ***S*** should begin with `1` or more **`digits`**.
> - After that, ***S*** should have `1` or more **`uppercase letters`**.
> - ***S*** should end with `1` or more **`lowercase letters`**.
## Solución: Solución propia.
### Cadena de la solución
```
"^\d+[A-Z]+[a-z]+$"
``` 
### Explicación de la respuesta

Explicación de como se cumple cada requerimiento:
- Debe empezar "^" con uno o mas "+" dígitos "\d".
- Debe tener una o mas "+" letras mayúsculas"\[A-Z]".
- Debe tener una o mas "+" letras minúsculas "\[a-z]".