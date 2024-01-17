# Comandos de git básicos
## git add <file>
Usa . como nombre de archivo para añadir todos los archivos untracked.
## git rm --cached <file>
Quita un archivo de la staging area.
## git status
Muestra el estado del worktree.
## git config --global
Modifica variables de configuración del git
Estas dos son necesarias para identificar el commit.
```
 git config --global user.name David
 git config --global user.email david@email.com
```
## git commit -m "<mensaje>"
Crea un commit con el mensaje <mensaje> y limpia el worktree. Guarda todos los cambios staged.
## git commit --amend -m "<mensaje>"
Añade cambios al último commit.
## git log --pretty=oneline
Muestra los commits de la rama actual con un estilo alternativo.
## git reset --hard <hash>
Elimina todos los commits a partir del commit identificado por hash.
Establece el commit con hash <hash> como base de la rama.
## git clone <src> <dst>
Clones a repository from path or url <src> to <dst>
## git commit -a -m "canvi 1"
Añade todos archivos a la staging area y hace un commit.
## git branch hotfix
Crea una rama
## git checkout hotfix
Cambia a la rama hotfix
## git checkout -b "hotfix"
Crea la rama hotfix y cambia a ella.
## git merge hotfix
Une la rama hotfix a la rama actual.
### Tipos de merge
- fast-forward merge
- Con conflictos
## git branch -d hotfix
Borra la rama hotfix
## git push origin -d bmovies
Borra una rama remota
