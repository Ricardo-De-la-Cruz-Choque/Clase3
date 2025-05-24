# comandos git
## registrar credenciales de usuario y correo
git config --global user.name "tiene que ir el nombre de usuario"
git config --global user.email "tiene que ir el correo con la que se registro la cuenta"

## guardar cambios en el area de preparacion
git add .
## asignar nombre a los cambios guardados
git commit -m "colocar cualquien nombre al cambio"
## enviar los cambios al repositorio en la nube
git push -u origin "tiene que ir el nombre de la rama (main)"
