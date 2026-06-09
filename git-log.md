# GIT LOG

El comando ```git log``` sirve para visualizar el historial de commits de tu proyecto. Te permite rastrear cronológicamente los cambios realizados, mostrando el *hash* identificador único, el autor, la fecha y el mensaje de cada confirmación.

## Sintaxis

```git log [<options>] [<revision-range>] [[--] <path>…​]```

## Opciones más útiles para personalizarlo

```--oneline```: Muestra cada commit en una sola línea compacta, ideal para tener una vista rápida de los últimos cambios.

```-p```: Despliega el historial mostrando exactamente qué líneas de código se agregaron o eliminaron en cada commit.

```--author="nombre"```: Filtra el historial para ver únicamente los cambios realizados por un colaborador específico.

```--since=<date>```: Busca y lista únicamente los commits creados a partir de la fecha indicada.

```--graph```: Dibuja un gráfico de texto en la terminal para visualizar cómo se han bifurcado y unido las diferentes ramas de trabajo.

```--all```: Muestra el historial de todas las ramas existentes en lugar de solo la actual.

```--patch```: Muestra el contenido exacto de los cambios (diff) introducidos en cada commit.

```--stat```: Muestra un resumen estadístico de los archivos modificados, incluyendo inserciones y eliminaciones

Para salir de la vista del historial de git log (si la lista es larga), simplemente se puede presionar la tecla ```q``` para salir.

### Ejemplos

```git log --oneline```

```git log --since="2 weeks ago"```