##  Docker en Heroku (Pendiente)

**Instalar el plugin**
```sh
heroku plugins:install heroku-docker
```

**Crear un Dockerfile.**
```
heroku docker:init
```

**Crea e inicia una nuevo contenedor.**
```
heroku docker:start
```

**Deploy tu imagen a heroku**
```
heroku docker:release
```
