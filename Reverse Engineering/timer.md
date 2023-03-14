## Descripción
You will find the flag after analysing this apkDownload [here](https://artifacts.picoctf.net/c/421/timer.apk).

## Solución
-  Pra poder resolver este reto se nos da un archivo  `timer.apk`.
- Como el archivo es `.apk`, no se puede visualizar el codigo, por lo que con la pagina [javadecompilers.com](http://www.javadecompilers.com/) descompilaremosel archivo .apk para visualizar el codigo.
- Al descompilarlo se nos dan muchas carpetas non muchos archivos, po lo que seria muy tardado buscar uno por uno, por lo que con el comando `grep -ri picoCTF` podremos encontrar la flag facimente gracias a la recursividad utilizada con el `-r`.
```bash()
picoCTF{t1m3r_r3v3rs3d_succ355fully_17496}
```

## Notas adicionales
- Al indicar **-ri** conseguimos que la búsqueda se realice dentro de todos los ficheros existentes en el propio directorio y en todos los **subdirectorios** internos.

## Referencias 
- [## ¿Cómo buscar en todos los ficheros dentro de un directorio y sus subdirectorios?](https://www.jabenitez.com/2013/08/02/buscar-texto-en-todos-los-ficheros-de-un-directorio-y-subdirectorios-en-linux/)