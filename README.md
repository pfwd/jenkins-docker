# Jenkins with Docker

## Install
```
$ docker-machine create jenkins
$ docker-machine env jenkins
$ eval $(docker-machine env jenkins)
$ docker-compose up -d --build
```