#Docker File para creacion de Imagen Java y arranque de microServicios spring boot
FROM openjdk:8-jdk-alpine
MAINTAINER Ismael Caballero
COPY order-api.jar /app.jar
EXPOSE 8080
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active-default", "/app.jar"]