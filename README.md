# docker-mongodb
para salir de la terminal docker -> exit


para exportar base de datos-> 
docker exec mongodb mongodump \
  -u admin \
  -p admin123 \
  --authenticationDatabase admin \
  --db test \
  --archive=/tmp/backup.gz \
  --gzip

  guardar archivo en local ->
  docker cp mongodb:/tmp/backup.gz ./backup.gz

  eliminar imagen ->
  docker images
  docker rmi abc123def4563