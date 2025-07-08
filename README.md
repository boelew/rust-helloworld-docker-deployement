# Hello World in Docker Container

## Build

`docker build -t helloworld -f containerfile .`

## Run Docker container

`docker run -it helloworld /bin/bash`

## Run Hello World

Navigate to /usr/src/app
`cd /usr/src/app`

Run application:
`./helloworld`