This is a working example of a multi-container flask application with postgres, mongo and redis as the database fronted by the nginx reverse proxy.

## Usage

1. Bring up the cluster
```bash
$ docker-compose up -d
```
//sudo docker-compose up primero se debe corer el servicio//
sudo docker ps //par continuar con el sigiente//
el cual debe escbribir el siguente udo docker exec -it 3aa106127b19 bash//
mongo --version en lo que consigue este comando llevaria a algo nuevo//
mongo d esta manera en minuscula cada comando siguiente//
show dbs//
use testdb//
show collections//
ahora sera primero este comando para la verificacio db.users.find()//
y por ultimo este comando que aplicaria en mostrar lo que se escribio db.posts.find()//

```https://github.com/lorenasegundo08/Flask_app/edit/master/README.md-- localizacion

11. Browse to localhost:8181 to see the app in action.
12. Browse to localhost:5151 to see the postgres manager.

13. Copiar url en el navegador para realizar un registro http://localhost:8181/signup
