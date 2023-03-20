FROM openjdk:11-jdk-slim

ARG JAR_FILE=target/*.jar

WORKDIR /app

COPY ${JAR_FILE} app.jar

EXPOSE 8080

USER 1001

ENTRYPOINT ["java","-jar","/app/app.jar"]