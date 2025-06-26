## Problema:

> You have a test string ***S***. Your task is to match the pattern  ***Xxxxxx***.
> Here, ***x*** denotes a word character, ***X*** and denotes a digit.  ***S*** must start with a digit ***X*** and end with ***"."*** symbol.  
> ***S*** should be ***6*** characters long only.
## Solución: Solución propia.
### Cadena de la solución

```
"^\d\w\w\w\w\.$"
``` 
### Explicación de la respuesta

Los requerimientos son:
- Que la cadena inicie con un carácter numérico, por lo que puse en la expresión "^\d", "^" representa el inicio de la cadena y "\d" representa un carácter numérico.
- Que la cadena termine con un ".", esa parte la cumple la siguiente secuencia "\.$" donde "\." representa el carácter ".".
- Que el resto de caracteres sean caracteres de palabras, esa parte la cumple la secuencia "\w\w\w\w" donde "\w" es un carácter de palabra.
- Que la cadena sea de 6 caracteres de largo, esa parte se cumple dado que debe iniciar con un numero y terminar con un punto quedan 4 caracteres, los cuales son de palabra.