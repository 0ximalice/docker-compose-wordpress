# docker-compose-wordpress
This repository contains the docker-compose of the example to deploy the official WordPress and MySQL in 5 minutes.

See, 
http://ggez.me/2017/05/30/install-wordpress-in-5-minute-with-docker/

# Requirements
- Docker, Docker-Compose 

To install docker and docker-compose, however, you also look at https://docs.docker.com/engine/installation to install into the difference OS
```ssh
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
$ sudo apt-get update
$ sudo apt-get install docker-ce docker-compose
```

# Building Our Image
```ssh
$ docker-compose up -d
```
