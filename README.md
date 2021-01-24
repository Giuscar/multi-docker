# Multi-docker
This is an example of multi-docker container for a simple React application calculating Fibonacci series. 

# Structure of docker containers for Development environment

![alt text](https://github.com/Giuscar/multi-docker/blob/master/img/devEnv.PNG)

# Structure of docker containers for Production environment
![alt text](https://github.com/Giuscar/multi-docker/blob/master/img/prodEnv.PNG)

# How to launch application
- docker-compose up -d --build 
- docker-compose.yml is configure to launch the containers in Dev environmnet. If you want to switch to prod, simply change the Dockerfile for each container from "Dockerfile.dev" to "Dockerfile"
