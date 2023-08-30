# Spring Boot Hello World

**A simple secured Spring Boot 2.x app  secured and integrated with keycloak **

## How to Run Application

**Start the application using any of the commands mentioned below**

> **Note:** First two commands need to run inside the root folder of this project i.e inside the **spring-boot-hello-world** folder


- **Using maven** <br/>``` mvn spring-boot:run```


- **Directly from IDE**
  <br/>```Right click on HelloWorldApplication.java and click on 'Run' option```
  <br/><br/>


<br/>

**Send an HTTP GET request to '/hello' endpoint using any of the two methods**

- **Browser or REST client**
  <br/>```http://localhost:8081/hello```


- **cURL**
  <br/>```curl --request GET 'http://localhost:8081/hello'```


## How to Run Unit Test Cases

**Run the test cases using any of the commands mentioned below**

> **Note:** These commands need to run inside the root folder of this project 

- **To run all the test cases**
  <br/>```mvn test```

