## What is it?
This source code is an Spring Boot web application (mvc + thymeleaf).
 
Tested with
* Docker 19.03.8
* Mac
* Java version: 1.8.0_211
* Spring Boot 2.2.4.RELEASE
* Maven 3.6.2


## How to run this?
```bash
$ git clone https://github.com/cnarra14/docker-spring-boot.git
$ cd docker-spring-boot
$ mvn clean package
$ java -jar target/spring-boot-web.jar

  access http://localhost:8080

//dockerize

// create a docker image
$ docker build -t spring-boot:1.0 .

// run it
$ docker run -d -p 8080:8080 -t spring-boot:1.0

  access http://localhost:8080
```