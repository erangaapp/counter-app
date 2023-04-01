# docker-console-app
This repository contains a small  counter app which can be run in a docker container

#Nessarary docker commands to run the App in a local docker container.
01. docker build -t counter-image -f Dockerfile .
02. docker create --name conter-app counter-image
03. docker start conter-app
04. docker stop conter-app
05. docker rm conter-app
06. docker rmi counter-image
07. docker run -it --rm counter-image 3
