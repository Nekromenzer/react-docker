# React Docker

This is a simple React app that is containerized using Docker. The app is built using the create-react-app tool.

## Build the Docker Image

`docker build -t react-docker .`

## Run the Docker Container

`docker run react-docker`

## Run with Port Mapping

`docker run -p 5173:5173 react-docker`
