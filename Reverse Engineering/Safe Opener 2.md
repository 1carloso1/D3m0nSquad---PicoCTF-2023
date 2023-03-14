
## Descripción
What can you do with this file? I forgot the key to my safe but this file is supposed to help me with retrieving the lost key. Can you help me unlock my safe?

## Solución
- Pra poder resolver este reto se nos da un archivo  `safeOpener.class`.
- Como el archivo es `.class`, no se puede visualizar el codigo, por lo que con la pagina [javadecompilers.com](http://www.javadecompilers.com/) descompilaremosel archivo .class para visualizar el codigo.
- Analizando el codigo dado, podemos ver que el codigo muestra directamente la flag sin necesitar de ejecutarlo.
```java()
 final String encodedkey = "picoCTF{SAf3_0p3n3rr_y0u_solv3d_it_b601de44}";
```

## Notas adicionales

## Referencias 