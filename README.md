# docker_basics
Learn docker with me


### installing dependencies in your docker
- go to docker hub
- docker pull ngnix
- docker pull ngnix:12.11.1  with version

### managing docker images

- docker images  - lists down all the images
- docker rmi nginx:imagetag  - delete the image
-  docker rm to remove a container

### containers
-  docker rm -f container name -  to delete forcely 
-  docker run -d -p 9090:80 nginx:alpine
-  d means detached mode and p stand for port at docker its 80 but at our local machine its 9090

### 3.4 - writing a docker file
