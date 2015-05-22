##  Contruir y correr

Construye una nueva imagen con la nueva app.

```sh
docker-compose build
```

Levanta el stack.

```sh
docker-compose up
```

Crea la base de datos.

```sh
docker-compose run web rake db:migrate
```
