# docker-cheatSheet

1. docker –version

This command is used to get the currently installed version of docker

2. docker pull

Usage: docker pull <image name>

This command is used to pull images from the docker repository(hub.docker.com)

3. docker run

Usage: docker run -it -d <image name>

This command is used to create a container from an image

4. docker ps

This command is used to list the running containers

5. docker ps -a

This command is used to show all the running and exited containers

6. docker exec

Usage: docker exec -it <container id> bash

This command is used to access the running container

7. docker stop

Usage: docker stop <container id>

This command stops a running container

8. docker kill

Usage: docker kill <container id>

This command kills the container by stopping its execution immediately. The difference between ‘docker kill’ and ‘docker stop’ is that ‘docker stop’ gives the container time to shutdown gracefully, in situations when it is taking too much time for getting the container to stop, one can opt to kill it

9. docker commit

Usage: docker commit <conatainer id> <username/imagename>

This command creates a new image of an edited container on the local system

10. docker login

This command is used to login to the docker hub repository

11. docker push

Usage: docker push <username/image name>

This command is used to push an image to the docker hub repository

12. docker images

This command lists all the locally stored docker images

13. docker rm

Usage: docker rm <container id>

This command is used to delete a stopped container

14. docker rmi

Usage: docker rmi <image-id>

This command is used to delete an image from local storage

15. docker build

Usage: docker build <path to docker file>

This command is used to build an image from a specified docker file

docker inspect [container ID] -> Get more info   about running container
docker volume -> create a docker volume
docker network -> create a docker network
docker build -> build a new image from dockerfile
docker login -> Login to docker account
