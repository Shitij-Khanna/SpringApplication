FROM openjdk:8-jdk-alpine
MAINTAINER Nitish Srivastava
VOLUME /tmp
EXPOSE 8068
ADD target/*.jar app.jar
ENTRYPOINT ["sh","-c","java -jar /app.jar"]