[![Docker](https://img.shields.io/docker/v/mariamihai/sbm-brewery-eureka?sort=date)](https://hub.docker.com/r/mariamihai/sbm-brewery-eureka)

# SFG Brewery Gateway Service
Spring Boot Microservice project.

## Description
The current project is part of the "Spring Boot Microservices with Spring Cloud" [Udemy course](https://www.udemy.com/course/spring-boot-microservices-with-spring-cloud-beginner-to-guru/). 

The project provides service discovery and it is used by all other applications for registration and communication between themselves.

An overview of all the projects involved can be found [here](https://github.com/mariamihai/udemy-sbm-overview).

## Docker images
Automatic building was not implemented for this project. The `latest` tag contains the best implementation considered 
appropriate to be used.

For automatic building of Docker images check the next projects:
- for [CircleCI](https://github.com/mariamihai/CIToDockerExampleProject)
- for [TravisCI](https://github.com/mariamihai/sma-overview) (all projects implemented under the "Spring Microservices in Action" book)

## Implementation details
### Properties
- the name of the application, used by Eureka and the other services 
```
spring.application.name=eureka
```
- application server port
```
server.port=8761
```
