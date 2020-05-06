# Instrucciones para conectar proyecto Android Studio al repositorio en Github

> Primero tendrás que haberte creado el equipo+repositorio de tu proyecto en el siguiente enlace: 
https://classroom.github.com/g/CzTeB0z6

1. Ahora sincroniza tu proyecto creado en Android Studio con ese repositorio, para ello y desde una terminal tipo Git Bash situate en la carpeta del proyecto y lanza los siguientes comandos:

	$ git init

	$ git add -A

	$ git commit -am "initial commit"

	$ git remote add origin https://github.com/2DAMUE/pfcjun20-tuequipo.git

	$ git pull origin master --allow-unrelated-histories
	(primero descargamos hacia nuestro AS los archivos que ya existen en Github con un pull antes de hacer nuestro push del código)
	(y si se abre el editor vi, tenéis que teclear tecla ESC y luego :wq con tecla Enter al final

	$ git push origin master


2. Una vez que tengas tu proyecto Android Studio creado y sincronizado, dentro de la carpeta "docs" en AS sustituirás la versión actual por tu versión de las plantillas de Anteproyecto y Memoria

> La coordinación del proyecto se realiza en el siguiente grupo de slack, si aún no estás únete ahora:
https://join.slack.com/t/pfcjun20-ue/shared_invite/zt-dqg4dajl-cUJZlD5uGW5q6cuktSvczQ
