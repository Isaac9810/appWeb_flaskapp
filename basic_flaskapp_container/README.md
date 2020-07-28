This is a working example of a multi-container flask application with postgres, mongo and redis as the database fronted by the nginx reverse proxy.

## Usage

1. Bring up the cluster
```bash
$ docker-compose up -d
```

3. Browse to localhost:8181 to see the app in action.
2. Browse to localhost:5151 to see the postgres manager.

# appWeb_flaskapp
sudo docker-compose up //primero debemos de correr el servicio de docker
sudo docker ps // muestra la id de mongo
sudo docker exect -it <id> bash //contenedor donde corre mongo
mongo --version
mongo
show dbs //permite listar las bases de datos disponibles
use testdb //para usar la bd donde estamos trabajando
show Collections //tablas en la bd
db.users.find() //ver los registros
db.posts.drop //vaciar la bd
Ctrl + c //detener el servicio de docker
