Remove all containers and volume in a one liner `docker rm -fv $(docker ps -a -q)`
https://coderwall.com/p/ewk0mq/stop-remove-all-docker-containers
https://linuxize.com/post/how-to-remove-docker-images-containers-volumes-and-networks/

docker system prune --volumes //remove all volumes

docker container ls -a //list all containers

(running postgres in docker)[https://www.saltycrane.com/blog/2019/01/how-run-postgresql-docker-mac-local-development/]
