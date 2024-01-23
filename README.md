# Docker Container
Containerize a node js app in a docker container

My Docker Hub Profile: https://hub.docker.com/u/teddymuli

## Requirements
1. NodeJS: https://nodejs.org/en/download/current
2. Docker Desktop: https://www.docker.com/products/docker-desktop/

## Installing the docker image
``` bash
docker pull teddymuli/node-app
```

## Running the docker container
``` bash
docker run -d -p 3000:3000 node-app:1.0
```

## Docker Commands
1. List Images
``` bash
docker images
```
2. List Containers
``` bash
docker ps
```
3. Start Container
``` bash
docker run -d <image_name>
```
4. Port binding
``` bash
docker run -d -p <port>:<conatiner-port> <image-name>
```
5. Stop a container
``` bash
docker stop <container-id>
```

## Installation
1. Clone the repository
``` bash
git clone https://github.com/TeddyMuli/Docker-Container.git
```
2. Install dependencies
``` bash
npm install
```
3. Run the app
``` bash
node src/index.js
```

## Creating a docker image

``` bash
docker build -t node-app:1.0 .
```
