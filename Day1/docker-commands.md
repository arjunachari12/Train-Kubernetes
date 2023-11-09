## Docker commands

```
docker version
docker info
Docker help
docker container run
docker run
docker search ubuntu
docker pull ubuntu
docker image ls
docker run ubuntu
docker run -d -p 8080:80 nginx
docker container run --publish 80:80 nginx
docker container run --publish 80:80 --detach nginx
docker container ls
docker container stop 
docker container ls
docker container ls -a
docker container run --publish 80:80 --detach --name webhost nginx
curl localhost:8080
docker container stop b006c59c1b99
docker container start b006c59c1b99
docker container rm b006c59c1b99
docker container rm -f b006c59c1b99
docker container run -d -p 3306:3306 --name db -e MYSQL_RANDOM_ROOT_PASSWORD=yes mysql
docker container run -d --name db -e MYSQL_RANDOM_ROOT_PASSWORD=true mysql:8.0
docker container run -it --name webserver nginx bash
docker container exec -it 4d5f71d77a05 bash

docker container run --publish 80:80 --detach --name webhost nginx
docker container logs webhost
docker container top webhost
docker container run -d --name mysql -e MYSQL_RANDOM_ROOT_PASSWORD=true mysql
docker container inspect mysql
docker container stats mysql

```

