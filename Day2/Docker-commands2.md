
# DELETE all containers

```
docker rm -f $(docker ps -a)
```
## Docker Networking
```
docker network ls
docker network inspect bridge
docker network ls
docker network create my_app_net
docker network ls
docker network create --help
docker container run -d --name new_nginx --network my_app_net nginx
docker network inspect my_app_net
docker run -d --network host --name my_nginx nginx
docker run --rm -dit --network none --name no-net-alpine alpine:latest ash
```
## Docker volume
```
docker container run -d --name mysql -e MYSQL_ALLOW_EMPTY_PASSWORD=True mysql
docker container inspect mysql
docker volume ls
docker volume inspect TAB COMPLETION
docker volume create mysql-db
docker container run -d --name mysql2 -e MYSQL_ALLOW_EMPTY_PASSWORD=True -v mysql-db:/var/lib/mysql mysql
mkdir html
#add index.html page under html folder
#add some text as “Welcome to Bind mount”

docker container run -d --name nginx -p 80:80 -v $(pwd):/usr/share/nginx/html nginx

```
