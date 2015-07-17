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

Tu primer Commit:

git commit -m "Tu primer commit"

Subirlo a github

git push origin master

Checar el estatus de tu repo:

git status

