## Problema:

> You have a test string ***S*** . Your task is to match the pattern  ***xxxXxxxxxxxxxxXxxx***
> Here ***x*** denotes any word character and ***X*** denotes any non-word character.
## Solución: Solución propia.
### Cadena de la solución

```
"\w\w\w\W\w\w\w\w\w\w\w\w\w\w\W\w\w\w"
``` 
### Explicación de la respuesta

- Secuencia "\W" : representa a cualquier carácter o conjunto de que no sea una palabra.
- Secuencia "\w" : representa una palabra o conjunto de caracteres.
