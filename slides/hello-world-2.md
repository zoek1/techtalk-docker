##  Iniciar el contenedor! - CLI


```sh
sudo docker run -it -p 8080:80 --name holamundo --rm sinapp ruby app.rb -o 0.0.0.0 -p 80
```
  - **-i**
    indica que va a crear una shell interactiva.

  - **-t**
    la asigna a la tty actual.

  - **-p**
    Liga el puerto local 8080 al puerto 80 del contenedor.

  - **--name**
    Le asigna un nombre al nuevo contenedor.

  - **--rm**
    Elimina el contenedor automáticamente después de que termina el proceso ejecutado.
