# COMANDO GIT REBASE

Git rebase sirve para actualizar tu rama tomando como base otra. Los programadores la utilizan bastante cuando quieren incorporar cambios muy recientes y tener un historial mucho más limpio.

# ¿COMO FUNCIONA GIT REBASE?

Lo que hace Git es agarrar los commits de tu rama y volver a aplicarlos encima de la rama de referencia. El resultado de esto es como si hubieras empezado a trabajar desde la versión mas nueva de esa rama.

# EJEMPLO

Si estas en una rama de desarrollo y queres traer los ultimos cambios de main:

<bash>
git rebase main
