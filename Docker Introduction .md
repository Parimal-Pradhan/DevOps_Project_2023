
# Docker For Devops Engineer?
![Add a heading](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/466b6b4c-5be0-4b75-b4ca-8b747e6e33f4)

## What is Docker?

Docker is a container technology where we can run our application using lightweight resources and we can wrap our entire application, build the image and will ship it to the environment in a container format. It is a lightweight resource to deploy your application.

## Difference between Virtual Machine and Docker Container
Virtual Machine (VM)	Docker Container
It takes huge resources to create a VM	It takes fewer resources
Need to install Guest OS	No Need to install Guest OS
Hardware Level Virtualization	OS level virtulization
Boot time in Minutes	Boot time in Milliseconds
Docker installation On EC2 (AWS)
Go to EC2 Console and Launch Instance

## Docker installation On EC2 (AWS)

#### Go to EC2 Console and Launch Instance
![inst1](https://github.com/parimal007/DevOps_Project_2023/assets/86794999/73b6bc5a-b272-45d7-b61f-0d698a149400)

### 1. First update system (the system will get updated)
       sudo apt-get update


Now the system is up to date. Let's install docker.

### 2. Docker installation

sudo apt-get install docker.io

### 3. Now check whether the docker service is active or not.

systemctl status docker

The docker installation is finished now. Let's understand docker commands.

## Docker Basic Commands

docker -v 

This command is used to see the version of a docker on your system.



docker pull <image name>: It is used to pull the images from the docker registry or docker hub.(https://hub.docker.com/)

e.g.docker pull ubuntu.



docker images: It is used to see all the images stored on the local hub.



docker run: It is used to run the container from the image

-it ==> interactive mode

-d ==> detached mode (it means it will run in the background)


docker run -it -d ubuntu


docker ps: It is used to check how many containers currently running now.



docker ps -a : It is used to list all containers running and stop state.



docker exec: To access the running container need to use docker exec.

docker exec -it eloquent_engelbart  bash
docker exec -it <container name> bash



docker stop: To stop the running container we can use this command.

docker stop <container id>

docker kill: docker stop command takes time to shut down the container so we can use docker kill to stop the container immediately.

docker kill <container id>

docker commit: This command is used to create an image of an edited container.

docker commit <commit id> <image name>

docker login: It is used to log in docker hub account.

docker login

docker push: This command is used to push the image to the docker hub.

docker push <image name>

docker rm: It is used to remove the stop containers.

docker rm <container id>

docker build: It is used to build an image from a Docker file.

docker build <docker file path>

Task
Use the docker run command to start a new container and interact with it through the command line.[Hint: docker run hello-world]
docker run :



How to see detailed information about the container or image?

docker inspect



docker port: command to list the port mappings for a container.



docker stats: command to view resource usage statistics for one or more containers.





docker top: command to view the processes running inside a container.



docker save: command to save an image to a tar archive.



docker load: command to load an image from a tar archive.



I hope you would like this blog. In the next blog, we will discuss docker architecture and many more.

Thank you for reading this blog.Happy Learning!!!!!



