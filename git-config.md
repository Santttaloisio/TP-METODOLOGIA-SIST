# Comando git config
### Este comando se usa para configurar datos y opciones que tiene Git, y una de las primeras cosas que se suele hacer luego de su instalacion es indicar el nombre de usuario y el correo electronico, porque esos datos quedan asociados a los commits que realizamos en un repositorio.
### Por ejemplo tenemos: 
-  git config --global user.name "Vladimir" 
-  git config --global user.email "vladimir@gmail.com"

### La opcion --global significa que esa configuracion se va a usar en todos los repositorios de la computadora (no solo en el repositorio actual), exeptuando algun repo que se configure distinto particularmente.

### Tambien se puede consultar la configuracion actual con:

- git config --list

### Obtenemos todas las configuraciones.

### O revisar un dato puntual: 
- git config user.name
- git config user.email

### Estos nos devuelve el nombre y el email que tenemos configurado.