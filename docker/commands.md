#ssh into ubuntu server
docker run --rm -it ubuntu:18.04 bash
docker ps
docker diff containerid
docker image ls
docker image rm imagename
docker container ls
docker volume rm $(docker volume ls -q)
docker image rm $(docker image ls -q)
docker-compose exec app composer require predis/predis
docker-compose up -d
docker-compose down
docker-compose ps
docker-compose run --rm node npm install
docker-compose run --rm node yarn install
docker images -a
