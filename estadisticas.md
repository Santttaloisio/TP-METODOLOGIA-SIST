# Estadisticas del repositorio (al momento de usar los comandos)

### Este archivo presenta las estadisticas del repositorio utilizadas para documentar el desarrollo del trabajo prractico de Git. 

Durante el trabajo usamos pull requests para no integrar los cambios directamente sobre la rama main.
Cada integrante trabajó en una rama propia, realizó sus commits y luego abrió un pull request para que el cambio pudiera ser revisado antes de incorporarse al repositorio principal.

Entendemos que un pull request es una instancia de revisión e integración de cambios que nos permite comparar una rama con main, revisar los archivos modificados, dejar comentarios, realizar correcciones y finalmente integrar esos cambios mediante un merge.
Tambien entendemos que si una pr esta abierta, se pueden seguir haciendo commits hasta que la pr se acepte o se solucionen conflictos.

# Integrante con mayor cantidad de commits

### Comando utilizado:

git shortlog -sn --all

### Resultado obtenido:

    14  Conrado Lanusse
     5  Laureano Kronemberger
     5  Vladimir Kozik
     4  santino
     4  vladimir
     3  Santttaloisio
     3  Vladimir


#El integrante que realizo la mayor cantidad de commits fue conrado con 14.

### Observación sobre los autores

Al revisar el resultado del comando git shortlog -sn --all, observamos que un integrante aparecia mas de una vez con nombres escritos de forma distinta.
Esto probablemente se debe a que la configuración local de git no era igual en todas las computadoras utilizadas por el. Git toma el nombre del autor desde la configuración de cada entorno, por ejemplo Windows, Ubuntu o una notebook diferente.

# Cantidad total de merges realizados

### Comando utilizado:

git log --merges --oneline

### Resultado obtenido: 18

- 369fc29 (HEAD -> docs/estadisticas, origin/main, origin/HEAD, main) Merge pull request #17 from Santttaloisio/revert-15-feat/introduccion-git
- b7c112c Merge pull request #15 from Santttaloisio/feat/introduccion-git
- 4d74def Merge branch 'main' into feat/introduccion-git
- 6e472a2 Merge pull request #16 from Santttaloisio/feat/nuevos-indices
- e11455b Merge pull request #13 from Santttaloisio/feat/git-clone-push-pull
- b8da033 Merge pull request #14 from Santttaloisio/fix/estilos
- 44b4ead Merge pull request #11 from Santttaloisio/git-rebase
- 9e36ddd Merge pull request #10 from Santttaloisio/feat/git-merge
- 052a00b Merge pull request #9 from Santttaloisio/feat/introduccion-git
- df173cf Merge main into/fix-estilos
- 04b805a Merge pull request #2 from Santttaloisio/feat/git-config
- 7b6bf83 Merge pull request #8 from Santttaloisio/feat/git-branch
- 75018bb Merge pull request #7 from Santttaloisio/feat/git-switch
- 8223be5 Merge pull request #6 from Santttaloisio/feat/git-status
- c8f0c94 Merge pull request #5 from Santttaloisio/feat/git-commit
- 5a183b8 Merge pull request #4 from Santttaloisio/feat/git-add
- 42a3457 Merge pull request #1 from Santttaloisio/feat/introduccion-git
- 2c949ea Merge pull request #3 from Santttaloisio/feat/git-init


# Conflicto prueba:
Se realizo la solucion del conflicto por medio de git hub aceptando los incoming changes.
### Cantidad de conflictos producidos : 1

![1](/capturas/1.jpeg)
![2](/capturas/2.jpeg)
![3](/capturas/3.jpeg)
![4](/capturas/4.jpeg)
![5](/capturas/5.jpeg)

- Hash asociado a la resolución e integración del conflicto: b7c112c.
- El commit b7c112c corresponde al merge del pull request donde el conflicto quedo resuelto e integrado en main.

# Revert prueba:

## Cantidad de revert producidos : 1

![revert](/capturas/6.jpeg)
![revert](/capturas/7.jpeg)

## Mensaje del commit:

- Revert "docs(indice): actualizar enlaces del trabajo"

## Merge del Pull Request de revert

El pull request de revert fue integrado a main mediante el siguiente merge commit: 369fc29

- El revert se realizó desde GitHub mediante la opción **revert** del pull request.

- Hash del commit de revert: 3abd075

# Cantidad de ramas:

## Comando utilizado:
git branch -r
- origin/HEAD -> origin/main
- origin/feat/git-config
- origin/feat/git-init
- origin/feat/git-log
- origin/feat/git-merge
- origin/feat/introduccion-git
- origin/main.
A partir del resultado , se contaron **6 ramas remotas reales**. 

No se consideró **origin/HEAD -> origin/main** como una rama independiente, porque funciona como referencia a la rama principal remota.

# Comando utilizado para revisar los commits y la cantidad de archivos modificados:



### git log --stat --oneline
A partir del resultado obtenido, se identificó que el commit con mayor cantidad de archivos modificados fue:8fd536a.
Mensaje: fix: Se agregó formato a los comandos
Cantidad de archivos modificados: 3
Archivos modificados:
- git-add.md
- git-commit.md
- git-status.md

### git show 8fd536a

captura-modificaciones.png
![Modificaciones](/capturas/captura-modificaciones.png)

