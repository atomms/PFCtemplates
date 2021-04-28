# Instrucciones para conectar proyecto Android Studio al repositorio en Github

> NO OLVIDES SUSTITUIR ESTE README POR CAPTURAS DE TU APLICACIÓN EN CUANTO LAS TENGAS

1. Sincroniza tu proyecto creado en Android Studio con ese repositorio, para ello y desde una terminal tipo Git Bash situate en la carpeta del proyecto y lanza los siguientes comandos:

	$ git init

	$ git add -A

	$ git commit -am "initial commit"

	$ git remote add origin https://github.com/2DAMUE/repositorio-equipo.git

	$ git pull origin master --allow-unrelated-histories

	// primero descargaremos hacia nuestro AS los archivos que ya existen en Github con un pull antes de hacer un push del código)
	// y si se abre el editor vi, tenéis que teclear tecla ESC y luego :wq con tecla Enter al final

	$ git push origin master


2. Una vez que tengas tu proyecto Android Studio creado y sincronizado, dentro de la carpeta "docs" en AS sustituirás la versión actual por tu versión de las plantillas de Anteproyecto y Memoria
