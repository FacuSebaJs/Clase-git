Comandos GIT:

- git init -> Inicializa git en tu proyecto

- git add <archivo> -> Registra el archivo en cuestion 
- git add <archivo> <archivo> -> Registra los archivos seleccionados
- git add . -> Registra todas las modificaciones

- git commit -m "nombre commit" -> Commit rapido solo con titulo
- git commit -> Abre un cajon para titulo y descripcion

- git remote add origin <enlace-repo> -> Conecta un proyecto con github
- git remote set-url origin <enlace-repo> -> Reasignar el proyecto a otro repo

- git push origin <rama> -> Pushea a la rama de origen.
- git push -> Pushea cambios a la rama en la que estas parado.

- git clone <enlace-repo> -> Descargas el repo entero desde github

- git pull origin <rama> -> Descargar cambios a la rama de origen
- git pull -> Descarga cambios a la rama en la que estas parado.

- git branch <nombre-rama> -> Crear rama pero sin pasaron a la rama
- git checkout -b <nombre-rama> -> Crear rama y nos pasamos a ella
- git checkout <nombre-rama> -> Cambiarse de rama

- git merge <nombre-rama> -> Fusionar la rama <nombre-rama> con la rama actual.

*Cuando una rama se crea, no se puede ver en el  repositorio hasta que sincronizamos
el remo y hacemos al menos 1 push*