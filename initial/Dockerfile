FROM openjdk:8-jdk-alpine
ADD target/ms-config-server.jar /opt/ms-config-server.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app.jar"]