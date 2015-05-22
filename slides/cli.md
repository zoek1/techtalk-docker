## Workflow

- Obtener un contenedor.

```sh
docker pull [ImagenBase]
```

- Construir un contenedor.

```sh
docker build -t [NombreImagen] .
```

- Crear e iniciar un contenedor.

```sh
docker run -it --name [NombreContenedor] [NombreImagen] [Comando]
```

- Detener un contenedor:

```sh
docker stop [NombreContenedor]
```
- Eliminar un contenedor

```sh
docker rm [NombreContenedor]
```
