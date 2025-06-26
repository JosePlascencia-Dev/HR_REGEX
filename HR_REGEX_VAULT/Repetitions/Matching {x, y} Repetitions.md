## Problema:

> You have a test string ***S***.  
> Your task is to write a regex that will match ***S*** using the following conditions:
> - ***S*** should begin with `1`or `2` **digits**.
> - After that, ***S*** should have `3` or more **`letters`** (both lowercase and uppercase).
> - Then **S** should end with up to **`3 .`** symbol(s). You can end with `0`to`3.` symbol(s), inclusively.
## Solución: Solución propia.
### Cadena de la solución
```
"^\d{1,2}[a-zA-z]{3,}\.{0,3}$"
``` 
### Explicación de la respuesta
Explicación de como se cumple cada requerimiento:
-  Debe empezar "^" con uno o dos "{1,2}" dígitos "\d".
- Debe seguir con tres o mas "{3, }" letras.
- Debe terminar "$" con 0 o 3 "{0,3}" puntos "\\.". 
