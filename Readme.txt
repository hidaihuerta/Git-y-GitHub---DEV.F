Comandos git en orden de acción

git --version
    Se usa para ver la versión de git (o simplemente si está instalado)

git init
    Para iniciar a usar git en la carpeta posicionada

git status
    Para revisar qué archivos están en staging area (sala de espera)

git add .
    Para añadir al SA todo lo que se encuentra en la carpeta
    git add *.jpg
        Añade todos los archivos con esa extensión
    git add Logo*
        Añade todos los archivos que se llamen logo sin importar su extensión
    git add Nombre de carpeta
        Añade una carpeta completa dentro del repositorio
    git add ./Nombre de carpeta
        lo mismo
    git add nombrredecarpeta/nombredearchivo.extension
        agrega un sólo archivo dentro de una carpeta

git reset nombredelarchivo
    Elimina del SA el archivo seleccionado
    No elimina el archivo de tu equipo local, sino del SA
* usar las mismas formas que en git add

git commit -m "mensaje de actualización"
    Se genera commit con el mensaje apropiado
git commit
    Sin asignar mensaje da paso a un mensaje con cuerpo

gitignore
    Para añadir archivos o carpetas que queremos ignorar en los commits
* usar las mismas formas que en git add

**antes de hacer un git add y commit debemos teclear ctrl+s para guardar los cambios en el archivo
