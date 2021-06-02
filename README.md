## Endpoints to implement

* POST /users  create the user
* POST /user/login  login to application


* GET /users get all the registered user(later will make it only for admin)
* GET /users/{id} get the user details
* GET /users/{id}/address get the address details of user 



## Tech Stack

  * Java 8
  * Spring Boot
  * JUnit 
  


## Running the application

To build application: 
mvn clean install


To run application: 
mvn spring-boot:run

To start application: 
http://localhost:8080/users


## Testing
mvn clean test


##To run in docker container
	build: docker build -t springio/gs-spring-boot-docker .
	run:   docker run -p 8080:8080 springio/gs-spring-boot-docker
### Documentation

Swagger2 documentation is available.

http://localhost:8080/swagger-ui.html#