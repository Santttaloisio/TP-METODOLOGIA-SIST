# Comando git init

### El comando git init sirve para iniciar un repositorio git dentro de una carpeta, ya que transforma una carpeta comun en una carpeta que Git puede empezar a reconocer y controlar.

### Cuando ejecutamos este comando git crea una carpeta oculta llamada .git y ahi se guarda la informacion interna del repositorio, como la configuración, las ramas y el historial de cambios.
## La carpeta .git no suele modificarse manualmente, porque contiene informacion interna que git necesita para manejar el repositorio, explorarla puede darnos un pantallazo de la organizacion de toda la informacion de los commits y ramas (como vimos en la documentacion/guias que subieron desde la cátedra) pero en la practica para trabajarno es conveniente tocarla.

### Por ejemplo podríamos crear una carpeta para un proyecto y después iniciar git dentro de ella con estos comandos (windows):

mkdir repo-metodologia
cd repo-metodologia
git init

### A partir de ahi,ya se pueden detectar cambios en los archivos del proyecto, pero igual, eso no significa que los cambios queden guardados automaticamente, ya que para guardar una versión en el historial primero hay que preparar los archivos con git add y después hacer un commit con git commit.

### En resumen, git init es el comando que se usa cuando queremos empezar a usar este sistema en un proyecto desde cero.