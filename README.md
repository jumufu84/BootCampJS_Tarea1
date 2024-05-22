Explicacion de la tarea.

- En primer lugar hice en mi carpeta en local un git init para inicializar el repo.

- Despues me fui a gitHub, cree el repo y me copié con protocolo ssh la url para poder sincronizar el repo local con el de la nube,

- Hice el add, commit y push de los cambios en local al repo local y después, para sincronizar los repos utilicé el commando git remote add origin (urlrepo) y despues un git push -u origin master

- Con la sincronización realizada, he creado la nueva rama con git checkout -b development y realice unos cambios en el archivo index.html. Despues hice el add, commit y git push --set-upstream origin development para subir la rama y los cambios.

- Posteriormente me he cambiado de rama a master con git checkout master y he realizado el merge con git merge development, no ha habido conflictos, así que he hecho el push al repo de github
