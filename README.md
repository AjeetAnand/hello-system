# hello-system can help you, How to use this image
Create a Dockerfile in your Node.js app project


# specify the node base image with your desired version node:<version>
FROM node:6              #Upadted your machine node version

# replace this with your application's default port
EXPOSE 80                #port is same as node server sarted port number

You can then build and run the Docker image:

14. $ docker build -t hello-system .   # docker build -t hello-system -f ./.Dockerfile .

15. $ docker run -it --rm --name MessageName hello-system

16. $ docker run -it -p 3000:80 --name MessageName hello-system # Our port and Containers port

17. $ docker run -it -p 3000:80 -v //d/DockerTest/.:/usr/src/app --name MessageName hello-system # change dynamic ie;nodemon

# for more info https://github.com/nodejs/docker-node/blob/master/README.md#how-to-use-this-image 




# Work with virtual machine
1. Docker -v

2. docker run hello-world

3. docker run -it ubuntu

4. ls

#create a container need to give name

5. docker run -it --name ContainerName ubuntu

6. ctrl+P-Q ==> docker ps # show the container status

7. docker attach ContainerName ==> connect with docker

8. exit ==> will close the container.

9. docker images

10. docker rmi -f imageName # to remove images

# docker ps # show the container status
11. docker rm -f ContainerName # will remaove the container

12. docker start ContainerName # Start in dettached mode #docker attach ContainerName ==> connect with docker

