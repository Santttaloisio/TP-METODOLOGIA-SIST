# COMANDO GIT MERGE

El comando `git merge ` sirve para unir los cambios realizados en una rama, con otra. Es una de las formas más comunes en un equipo de integrar lo que cada participante hizo en su rama.

### ¿Como funciona GIT MERGE? Al ejecutar este comando, GIT toma todos los commits realizados de la rama que queremos integrar, y los combina en la rama en la cual estamos parados en ese momento.

### Al hacer GIT MERGE corremos el riesgo de que surgan conflictos. No son graves. Pero pueden suceder, ya que cuando en 2 ramas distintas se modificaron las mismas lineas. GIT no es capaz de decidir cual de ambas conservar. Para poder seguir trabajando sin conflictos, alguno de los integrantes tiene que resolverlo decidiendo que linea dejar.

### Un ejemplo de GIT MERGE puede ser que cuando estamos trabajando en una rama de desarrollo y queremos integrar lo que se hizo en esta rama en la main. Se puede utilizar:

# (consola parado en la rama main)

# git merge desarrollo
