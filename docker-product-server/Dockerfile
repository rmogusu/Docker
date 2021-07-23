FROM openjdk:8-jdk-alpine
MAINTAINER baeldung.com
COPY target/docker-product-server-0.0.1-SNAPSHOT.jar product-server.jar
ENTRYPOINT ["java","-jar","/product-server.jar"]
