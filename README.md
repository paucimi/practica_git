# practica_git
Practica de Git donde ponemos a prueba nuestros conocimientos en el manejo de la herramienta de control de cambios.

11.git reset --hard HEAD~1 deshacemos el último commit (perdiendo los cambios realizados en el working copy).

12.git reflog muestra el registro de todas las operaciones que he realizado en el repositorio, incluyendo los commits que he eliminado.Identificamos el hash y rehacemos el último commit con git reset --hard <hash>.

13.git checkout styled primero me aseguro de estar en la rama 'styled'.
git merge main styled absorbe a main
git commit -m formalizamos los cambios en el historial del repositorio.

19.git checkout styled para asegurarme estar en la rama "styled" donde voy a incorporar los cambios.
git merge htmlify fusiono la rama "htmlify" con "styled"

21. git checkout main para cambiar a la rama main
git merge styled

25. git log --graph --oneline --decorate

26.git merge --no-ff title

27.git log para ver el hash
git reset --soft para deshacer el merge sin perder los cambios.

28.git reset HEAD para descartar los cambios

29.git branch -d title

30.git merge main ya que es la rama de origen del merge

32.git reflog para ver listado de los distintos posicionamientos.
git checkout hash_del_commit_inicial, ahora he hecho un switching to hash.Me encuentro detached HEAD.

33.git log para ver historial de commits y busco el commit donde se menciona el cambio de título.