# Acordeón Git

### $ git init
    -inicializa un nuevo repositorio

### $ git status
    -Muestra el estado actual del repositorio

### $ git config --global user.name
    -Establece el nombre del desarrollador

### $ git config --global user.email
    -Indica el correo electronico del desarrollador

### $ git config  --global core.editor
    - Indicar el editor por default

### $ add
    -  empieza seguir uno o mas archivos :
         -A agrega todos los archivos delrepositorio

### $ git commit
    -  registra el nuevo estado y loregistra enlahistoria del repositorio
        -m <Descripcion del cambio>

### $ git log 
    - muestra la historia de commits que sehan hecho en un proyecto
        --online muestra cada entrada en una sola linea
        <archivo> se muestra  la historia solo de ese archivo

.gitignore
	-Este archivo nos permite ignorar archivos o directorios que no queramos darles seguimientos 


### git checkout <-idcommit> 
	- Regresas alestado seleccionado

### git revert <-idcommit>
	- revierte cambios realizados en ese estado

### $ git reset 
	-Resgresa al ultimo estado guardado, borrando permantemente cualquier cambio en el area depruebas
	- lleva labandera --hard

### $ git clean -f 
	- Borra permanentemente los archivosnoseguidos 


### $ git branch
	- lista las ramas existentes en el proyecto
	<nombre> se crea la rama con ese nombre 
### $ git merge
	- fuciona dos ramas,fusiona una rama objetivo con la rama donde nosencotramosactualmenmte 
	-recibecomoparametro la rama objetivo
