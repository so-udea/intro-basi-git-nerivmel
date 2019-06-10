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


