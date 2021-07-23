FROM openjdk:8-jdk-alpine
MAINTAINER baeldung.com
COPY target/docker-message-server-0.0.1-SNAPSHOT.jar message-server.jar
ENTRYPOINT ["java","-jar","/message-server.jar"]
