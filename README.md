Firstly, you must run this command : mvn clean package docker:build
after the image built then docker run -p 8080:8080 springio/spring-hateoas

Sample Request : http://localhost:8080/greeting?name="XX"
