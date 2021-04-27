## Comandos Git

## git init
>este comando inicia nuestro repositorio de git, personal
## git add .
>Agregar todos los cambios hechos a los archivos
## git commit "comentario"
>se genera un historial del repositorio y pasa a la memoria estatica
## git status
>muestra los archivos los cuales no se les han aplicado git add
26/04/2021
## git show
>muestra el ultimo commit 
## git log
>muestra el historial de commits 
## git diff <tag> <tag>
>compara versiones de commits
## git reset -- hard <tag>
>este es un reset "duro": elimina todos los commits antes del tag que escogimos
## git reset -- soft
>elimina lo que esta en el stagin pero no borra los cambios que tenemos sin git add o gurdar 
## git restore <archivo>
> similar al git reset -- hard pero no borra lo que este en la memoria ram 