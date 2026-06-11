# GIT SWITCH

El comando `git switch` es el mecanismo moderno de Git para cambiar entre ramas de trabajo. También permite crear ramas nuevas.
Se introdujo para desacoplar algunas tareas de `git checkout`, que se usaba para de demasiadas cosas.

## Sintaxis

`git switch [<options>]`

## Opciones más útiles para personalizarlo

`git switch <branch>`: Cambia a la rama objetivo.

`git switch -c <branch>`: Crea una nueva rama y cambia a la misma. Es equivalente al transaccional:
```  
$ git branch <new-branch>
$ git switch <new-branch>
 ```

`git switch -c <new-branch> <origin>`: Cambia a una rama nueva creada a partir de una rama de origen.

`git switch -`: Vuelve a la rama anterior.

`git switch --track <remote-branch>`: Crea una rama local siguiendo una rama remota.

`-git switch --detach <commit>`: Cambia a un commit específico. Equivalente a `git checkout <commit>`.

### Ejemplos

`git switch master`

`git switch -c feature/NewTask-1234`

`git switch --detach a1b2c3d`
