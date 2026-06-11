# GIT BRANCH

El comando ```git branch``` sirve para listar, crear, renombrar y eliminar ramas en Git.


## Opciones más útiles para personalizarlo

```git branch --list | -l | [no-option]```: Muestra todas las ramas locales, resaltando la rama de trabajo actual.

```git branch --remotes | -r```: Muestra todas las ramas remotas.

```git branch --all | -a```: Muestra combinación de ramas locales y remotas .

```git branch <new-branch>```: Crea una nueva rama con el nombre dado.

```git branch --move | -m```: Mueve/renombra una rama, junto a su configuración y reflog.

```git branch --delete | -d```: Elimina una rama.

### Ejemplos

```git branch feature/NewTask-1234```

```git branch -l```

```git branch -d fix/Issue-1234```