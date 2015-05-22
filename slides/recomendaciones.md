##  Recomendaciones

- Mantener tus contenedores en tu propio registry:
  https://registry.hub.docker.com/_/registry/

- Si deseas mantener multiples procesos dentro de un contenedor:
  https://registry.hub.docker.com/u/phusion/baseimage/

- Requieres tener automatizados tus procesos:
  http://docs.ansible.com/docker_module.html

- Si solo vas a ocupar una vez un contenedor, crealo con la opción --rm

- Remueve imágenes que ya no ocupes, pueden agotar tu disco duro.

- Iniciar procesos automáticamente con tu manejador de procesos:
  http://docs.docker.com/articles/host_integration/

- "Proteje" tu conexión con HTTPS:
  http://docs.docker.com/articles/https/
