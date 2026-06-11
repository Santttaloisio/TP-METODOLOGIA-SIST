# COMANDO GIT REVERT

El comando Git revert sirve para deshacer los cambios realizados por un commit anterior sin eliminarlo del historial del repositorio.

# ¿COMO FUNCIONA?

Cuando ejecutamos este comando, Git crea un nuevo commit que realiza la operación contraria al commit que seleccionamos. De esta manera, los cambios quedan anulados pero el historial del proyecto sigue conservándose.

A diferencia de otros comandos que modifican el historial, git revert mantiene todos los commits registrados, lo que lo convierte en una opción segura cuando se trabaja en equipo.

# ¿CUANDO SE UTILIZA?

Git revert suele utilizarse cuando se realizó un cambio incorrecto y se desea volver al estado anterior sin borrar información del repositorio.

También es útil cuando los cambios ya fueron compartidos con otros integrantes del proyecto y no conviene modificar el historial existente.

# EJEMPLO

Si queremos revertir un commit específico, debemos indicar su hash:

<bash>
git revert a1b2c3d

Luego Git generará automáticamente un nuevo commit que deshará los cambios realizados por ese commit.
