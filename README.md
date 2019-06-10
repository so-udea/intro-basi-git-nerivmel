# Laboratorio git parte 1

[git - la guía sencilla](http://rogerdudler.github.io/git-guide/index.es.html)

## Parte 1 ## 

Teniendo instalado git crear en la terminal un proyecto llamado **demo** reproduciendo los siguientes comandos:

```bash
git init demo (cd into it)
touch readme.md
git add readme.md
git reset readme.md
git add readme.md (to get it back in the staging area)
git commit -m 'creando un readme vacio'
```
Capture una imagen donde se evidencie lo que se hizo anteriormente llamandola figura1.png y guardela en demo.

## Parte 2 ##

Empleando el editor favorito copie y pegue el siguiente codigo dentro del readme:

```markdown
# Agenda
## ¿Qué hace un Sistema Operativo? ##
* Definición de los Sistemas Operativos
* Virtualización de Recursos
* Objetivos de diseño de los Sistemas Operativos
```

Guarde y ejecute los siguientes comandos:

```bash
clear
git status 
git diff
git add readme.md 
git status 
git commit -m 'Actualizando readme con la agenda del dia'
git status 
git log
```

Capture una imagen donde se evidencie lo que se hizo anteriormente llamandola figura2.png y guardela en demo.

```bash
clear
git status
git diff
git add *.png
git commit -m 'Agregando las capturas de evidencia'
git status
git log
```

## Parte 3 ##

Crear un nuevo repositorio en github tal y como se explica en el siguiente [enlace](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line) nombrelo como **lab0-repo**
dejando las demas opciones como aparecen por default El comando estrella aqui es **git remote add origin REPO_LOCATION**. Luego ejecute los siguientes comandos dentro del repo demo:


```bash
git remote add origin https://github.com/tigarto/lab0-repo.git 
git push -u origin master
```

Si se le pide origen y password coloquelos para que se actualice el repositorio. Luego en el navegador visualice el repositorio; si todo esta bien este se encontrará ya actualizado. Haga una captura de pantalla (llamela figura3.png) que evidencie el repositorio actualizado en el browser. Luego actualice el repositorio local empleando los siguientes comandos:

```bash
clear
git status
git add *.png
git status
git commit -m 'Agregando evidencia github'
git status
git log
```
Ahora, actulice el repositorio remoto:

```bash
git push -u origin master
```

Ahora, actulice el repositorio remoto, notara que ya se encuentra la captura figura3.png en el repositorio en github.









