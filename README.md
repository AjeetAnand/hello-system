# hello-system can help you, How to use this image
Create a Dockerfile in your Node.js app project


# specify the node base image with your desired version node:<version>
FROM node:6              #Upadted your machine node version

# replace this with your application's default port
EXPOSE 80                #port is same as node server sarted port number

You can then build and run the Docker image:

$ docker build -t hello-system .
$ docker run -it --rm --name hi hello-system

# for more info https://github.com/nodejs/docker-node/blob/master/README.md#how-to-use-this-image