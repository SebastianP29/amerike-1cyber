# Aprendiendo _GIT_

# Comandos de la configuración Global

Estos comandos los ejecutas la primera vez que vas a configurar tu información en la computadora donde trabajarás con _GIT_.

```bash
git --version
git config --global user.name "Jonathan MirCha"
git config --global user.email jonmircha@gmail.com
git config --global user.ui true
git config --global init.defaultBranch main
git config --list
# asignando visual studio code como editor de configuración de git
git config --global core.editor "code --wait"
git config --global -e
# para estandarizar los saltos de línea en windows
git config --global core.autocrlf true
# para estandarizar los saltos de línea en linux/mac
git config --global core.autocrlf input
# ver todas las opciones de la configuración en la terminal
git config -h
# ver todas las opciones de la configuración en el navegador
git help config
```

## Flujo básico de _GIT_

![Flujo](https://jonmircha.com/img/blog/git-flow.png)

## Inicializar _GIT_ por primera vez 
```bash
# git init se ejecuta una sola vez en cada carpeta,para indicarle a git que tiene  que supervisar dicha carpeta.
git init
#git remote add origin url vincula nuestro repositorio de github con la carpeta.   nombre-usuario/nombre-repositorio
git remote add origin https://github.com/SebastianP29/amerike-1cyber.git
# git status sirve para revisar el estado de los archivos de la carpeta que git está supervisando.
git status
# git log, permite conocer todo el historial de un proyecto, con la información de la fecha, el autor y id de cada cambio.
git log
# agregar los cambios de un archivo al staged
git add archivo/directorio
# agregar todos los cambios de todos los archivos al staged
git add .
# saca del stage y regresa al working directory el archivo indicado
git rm --cached archivo
# los cambios son comprometidos en el repositorio
# debes escribir el mensaje del cambio
# cuando se abra el archivo de configuración
# al terminar guarda y cierra el archivo
# para que los cambios tengan efecto
git commit
# es un shortcut del comando anterior
# escribes y confirmas el mensaje del cambio en un sólo paso
git commit -m "mensaje descriptivo del cambio"
# se agrega el origen remoto de tu repositorio de GitHub
git remote add origin https://github.com/usuario/repositorio.git
# la primera vez que vinculamos el repositorio remoto con el local
git push -u origin master
# para las subsecuentes actualizaciones, sino cambias de rama
git push
#para descargar los cambios del repositorio remoto al local
git pull
```