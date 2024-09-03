# HACK - GIT 1

##### ### ## ENVIAR UN COMMIT AL REPOSITORIO REMOTO.

-Crear un nuevo repositorio en github nombre: git_h_1

-Crear un repositorio local

-git init

-Registrar el repositorio remoto con tú repositorio local

-git remote add origin (pegar_la_ruta_del_repositorio_local)

-Verificamos la ruta remota

-git remote -v

- crear un archivo llamado lista_de_usuarios.txt

-touch lista_de_usuarios.txt

-Examinar la creación del archivo

-ls -l

-Agregar el archivo lista_de_usuarios.txt al stage(marcarlos para commitear)

-git add lista_de_usuarios.txt

-Verificamos el status

-git status

-Se realiza el commit

-git commit -m "feat: add lista_de_usuarios.txt"

-Verificamos el commit

-git log --oneline

-cambiar el nombre del ambiente (rama)

-git branch -M main

-Hacemos push

-git push -u origin main

-Verificamos el repositorio remoto en github para ver el push enviado

##  FIN.
