# ReactFluxTemplate
A javascript development environment to work with react and flux

OS: MacOS
Javascript Development Environment using: 
	- node
	- Browserify
	- Gulp
	- Bootstrap
	- ESLint
	- SublimeText3

1º Instalar XCode desde la app store.

2º Instalar Homebrew: package manager para MacOs

	ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
	
	Para ver versión de Homebrew: brew -v

3º Instalar node.js
	
	brew install node
	
	Para ver versión de node: node -v
	Para ver veersión de npm : npm -v

4º Inicializar npm sobre el directorio de trabajo. (Ir al home directory de la app que estamos desarrolando)

	npm init 

	Completar los datos que se piden sobre el usuario, github, etc... 
	Se creará un fichero package.JSON. Para verlo cat package.JSON (type si es MSDos)

5º Instalar Gulp para automatizar tareas como el build de la aplicación.

	npm install --save gulp gulp-connect gulp-open
	
6º En el home del proyecto crear dos carpetas src y dist. En la primera van los fuentes, y en dist los ficheros
copiados, browserifados y concatenados.

7º Instalar Browserify para hacer que los ficheros js se puedan ver en un browserifados, reactify para compilar
   ficheros jsx (react) y vinyl-source-stream para poder usar conventional text stream con gulp
	
	npm install --save browserify reactify vinyl-source-stream

8º Instalar bottstrap y jquery para la UI y gulp-concat para concatenar los ficheros js en un único fichero

	npm install --save bootstrap jquery gulp-concat
	
9º Añadir referencias a jquery y a bundle/css en el main.js (ver fichero main.js)

10º Instalar ESLint

	npm install --save gulp-eslint
	
11º Crear fichero en el home con la configuración de ESLint (ver eslint.config.json)

12º Instalar React, React router y flux-starter-kit

	npm install --save react react-router flux

13º Guardar el fichero gulpfile.js en el home del proyecto.

