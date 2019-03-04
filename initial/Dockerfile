FROM openjdk:8-jdk-alpine
ADD target/gs-spring-boot-docker-0.1.0.jar /opt/gs-spring-boot-docker-0.1.0.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/opt/gs-spring-boot-docker-0.1.0.jar"]