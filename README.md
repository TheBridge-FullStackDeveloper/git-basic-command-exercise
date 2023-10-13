## Ejercicio de Git - Creación de Funciones en index.js con Commits
Este ejercicio te guiará a través de los comandos básicos de Git, desde la clonación de un repositorio hasta la creación de funciones en un archivo index.js, junto con la realización de dos commits distintos, uno para cada función.

Pasos:
Abre tu terminal o línea de comandos.

Haz un fork del repositorio, para poder obtener una copia del repositorio en tu cuenta de GitHub.

Clona un repositorio de ejemplo, desde el botón verde "Code" en GitHub, copia la URL SSH del repositorio.

```sh
git clone git@github.com:[NOMBRE_USUARIO]/git-basic-command-exercise.git
```
Sustituye git@github.com:[NOMBRE_USUARIO]/git-basic-command-exercise.git con la URL del repositorio que deseas clonar.

Ingresa al directorio del repositorio clonado:

```sh
cd repositorio
```
Crea un archivo index.js con el editor de texto o con el comando touch:

```sh
touch index.js
```

Crea una función simple de suma en el archivo index.js.

```javascript
function sum(a, b) {
  return a + b;
}
```
Guarda los cambios en el archivo index.js.

Verifica el estado de los cambios en tu repositorio local:

```sh
git status
```
Esto mostrará el archivo index.js modificado en rojo.

Agrega el archivo index.js al área de preparación:

```sh
git add index.js
```
Realiza un commit de los cambios con un mensaje descriptivo que explique la creación de la primera función:

```sh
git commit -m "Creation of sum function"
```
Asegúrate de que los alumnos proporcionen mensajes descriptivos.

Crea una segunda función resta en el archivo index.js.

```javascript
function subtract(a, b) {
  return a - b;
}
```
Guarda los cambios en el archivo index.js.

Verifica el estado de los nuevos cambios:

```sh
git status
```
Esto mostrará el archivo index.js modificado en rojo.

Agrega el archivo index.js al área de preparación:

```sh
git add index.js
```
Realiza un segundo commit con un mensaje descriptivo que explique la creación de la segunda función:

```sh
git commit -m "Creation of rest function"
```
Envía los cambios al repositorio remoto:

```sh
git push
```
Verifica que los cambios se hayan reflejado en el repositorio remoto visitando el repositorio en GitHub u otra plataforma de alojamiento de código.

El historial tiene que ser así:

```
* Creation of rest function
|
* Creation of sum function
|
* First Commit
```

Con estos pasos, los alumnos habrán creado dos funciones en el archivo index.js y habrán realizado dos commits distintos, uno para cada función. Esto les permitirá practicar la creación de funciones y la gestión de versiones con Git.