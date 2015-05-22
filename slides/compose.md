##  Compose

*docker-compose.yml*
```yml
db:
  image: postgres:9.4
  ports:
    - "5432"
web:
  build: .
  command: bundle exec rails s -p 3000 -b '0.0.0.0'
  volumes:
    - .:/myapp
  ports:
    - "3000:3000"
  links:
    - db
```

**Crear una app**
```sh
docker-compose run web rails new . --force --database=postgresql --skip-bundle
```

**Cambiar usuario:grupo de archivos**
```
sudo chown -R user:user .
```
