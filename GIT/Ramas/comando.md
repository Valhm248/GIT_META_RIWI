# Comando para listar las ramas

git branch

# Comando para crear una nueva rama

git branch nombreRama

# Comando para eliminar rama

git brach -D nombreRama

# Comando entre ramas

git switch nombreRama
git checkout nombreRama
git checkout -b nombreRama

# Desvincular un archivo de git que se le estaba dando seguimiento

git rm --cached nombreArchivo

# Crear una nueva versión con archivos que ya se estaban dando seguimiento

git commit -am "Nombre del commit"

# Comando para unir ramas

git merge nombreRama