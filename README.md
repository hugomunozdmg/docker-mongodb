# docker-mongodb
para salir de la terminal docker -> exit


para exportar base de datos-> 
- export -> crea el archivo dentro del contenedor docker
- export:save -> copia ese archivo a local

para importar base de datos ->
- import:copy -> copia el archivo que tengamos en local, al contenedor docker
- import -> incluye el archivo que tenga en el contenedor a la base de datos

  eliminar imagen ->
  docker images
  docker rmi abc123def4563



para usar base de datos pokemon ->
db.samples_pokemon.find()