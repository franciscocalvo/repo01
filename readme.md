# Creación de un repositorio local

-Creamos una carpeta y dentro de ella, mediante la consola escribimos:
```
git init
```
# Creación de fichero y guardado de estado

-Después de haber creado un fichero realizaremos el siguiente comando:
`git status`  
-Dicho comando nos mostrará el estado del repositorio, sean archivos modificados,carpetas nuevas, etc..  
-Tras comprobar que nuestro archivo no se está trackeando, lo añadimos con: `git add` \.   
-Si comprobamos con `git status` de nuevo, veremos que nuestros cambios ahora están implementados.  
-Realizamos un `git commit -m "mensaje"` para finalizar el conjunto de cambios junto con un comentario  explicativo de lo realizado y ya estaríamos preparados para realizar un `git push`.  

![Captura](/capturas/ej1.PNG "MarineGEO logo")

# Enlazar con el repositorio de GitHub
-Creamos un repositorio en GitHub, al realizarlo, GitHub nos mostrará la manera de enlazar nuestro repositorio local con el remoto  

```
git remote add origin https://github.com/franciscocalvo/repo01.git
git branch -M main
git push -u origin main
```