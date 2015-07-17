# Ejemplo_Github
Ejemplo de GitHub practico

Una vez instalas GitHub debe configurarse:
git config --global user.name "Angel"
git config --global user.email "jose110292@hotmail.com"

Generando la Public Key:
ssh-keygen

Te aparecera una direccion de donde se creo y la leeras con el comando:
cat ~/.ssh/id_rsa.pub

Arrancando tu proyecto:
git init

Creando un nuevo archivo:
touch README

Añadiendo un nuevo archivo:
git add README 
si deseas subir todos los archivos puedes poner
git add .
esto subira todos los archivos que tengas en tu repo local

Tu primer Commit:
git commit -m "Tu primer commit Descripcion"

Creando un nombre para el repo:
git remote add http-del-repositorio-en-la-pagina-de-git

Checar el estatus de tu repo:
git status

Subirlo a github
git push origin master (origin es el nombre el repo, master es la rama)

Para obtener todo el repo:
git pull origin master

###############################################
Para tabajar en branches

para crear una nueva rama
git branch nombre-de-la-nueva-rama

para cambiar entre ramas
git checkout nombre-de-la-rama-a-la-que-quieres-ir

