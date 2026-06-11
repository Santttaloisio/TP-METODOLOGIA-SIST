# COMANDO GIT MERGE

El comando `git merge` sirve para unir los cambios realizados en una rama con otra. Es una de las formas más comunes de integrar el trabajo realizado por distintos integrantes dentro de un mismo proyecto.

### ¿Cómo funciona Git Merge?

Al ejecutar este comando, Git toma todos los commits realizados en la rama que queremos integrar y los combina con la rama en la que estamos posicionados en ese momento.

### Conflictos en Git Merge

Al realizar un merge pueden aparecer conflictos. Esto sucede cuando dos ramas modificaron las mismas líneas de un archivo y Git no puede determinar automáticamente cuál de los cambios conservar.

Cuando ocurre un conflicto, alguno de los integrantes debe revisarlo y decidir qué cambios mantener para poder continuar trabajando normalmente.

### Ejemplo

Supongamos que estamos posicionados en la rama `main` y queremos incorporar los cambios realizados en una rama llamada `desarrollo`:

<bash>
git merge desarrollo

### Conclusión

Git merge se utiliza para combinar los cambios realizados en distintas ramas y reunir el trabajo de todos los integrantes en una misma línea de desarrollo.
