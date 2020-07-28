This is a working example of a multi-container flask application with postgres, mongo and redis as the database fronted by the nginx reverse proxy.

## Usage

1. Bring up the cluster
```bash
$ docker-compose up -d
```
sudo docker-compose up
sudo docker ps
sudo docker exec -it 3aa106127b19 bash
mongo --version
mongo
show dbs
use testdb
show collections
db.users.find()
db.posts.find()

```

11. Browse to localhost:8181 to see the app in action.
12. Browse to localhost:5151 to see the postgres manager.

13. Copiar url en el navegador para realizar un registro http://localhost:8181/signup
