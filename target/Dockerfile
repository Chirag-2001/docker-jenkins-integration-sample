FROM openjdk:8-jdk-alpine

COPY ./my-app-1.0-SNAPSHOT.jar /usr/app/

WORKDIR /usr/app

#EXPOSE 8081

ENTRYPOINT ["java", "-jar", "my-app-1.0-SNAPSHOT.jar"]


