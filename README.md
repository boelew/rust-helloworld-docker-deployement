# Hello World in Docker Container

This repository creates a simple Rust application that can be build on a local machine and can be deployed in a Docker container.
It can be used to get familiar with this kind of deployement.

## Build

`docker build -t helloworld -f containerfile .`

## Run Docker container

`docker run -it helloworld /bin/bash`

## Run Hello World

Navigate to application directory:
`cd /usr/src/app`

Run application:
`./helloworld`