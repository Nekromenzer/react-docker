# React Docker

This is a simple React app that is containerized using Docker. The app is built using the create-react-app tool.

## Install Docker

[Install Docker](https://docs.docker.com/get-docker/)

## Build the Docker Image

`docker build -t react-docker .`

## Run the Docker Container

`docker run react-docker`

## Run with Port Mapping

`docker run -p 5173:5173 react-docker`

## with real-time updates

`docker run -p 5173:5173 -v "$(pwd):/app" -v /app/node_modules react-docker`

## useful commands

`docker ps` - list all running containers

`docker ps -a` - list all containers

`docker stop <container_id>` - stop a running container

`docker rm <container_id>` - remove a container

`docker images` - list all images
