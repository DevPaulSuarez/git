git ini (inicilizar el git)

git add <nombre del archivo>
git add .       |\
git add -A	||> agrega Todos los archivos Modificados
git add --all	|/

git commit -m "Descripcion del cambio que se realizo"

git log  
git Status (verificar el estado del documento en el area de preparacion)
git diff (verificar las modificaciones)


git show 
git log --oneline

git checkout <id commit>

git stash 
git stash list
git stash apply
git stash clear

git branch
git branch "home"
git checkout -b develop (creacion de una rama llamda develop)
git checkout -b "feat/index"
git merge feat/index (merge para fusionar ramas)
git branch -D feat/index (eliminar la rama despues de pasar a produccion)
