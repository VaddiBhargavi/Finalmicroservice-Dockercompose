#This file indicates we are using the jdk11 and copying the target to app.jar, exposing to server port
FROM openjdk:11
COPY ./target/config-service-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8891
ENTRYPOINT ["java","-jar","app.jar"]