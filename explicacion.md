## Crear un repositorio local de GIT


git init (Inicializamos el repositorio local)


## Renombrar la rama de master a Main
git branch -M main

## Añadir un origen remoto (a donde vamos a subir nuestro codigos)

git remote add origin https://github.com/maurogit808/Repo-de-prueba.git


## Enviar el ult commit a la rama principal
git push -u origin main

# Una vez ya creado el repo y quieran subir algun cambio

git add .
git commit -m "mensaje"
git push