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
