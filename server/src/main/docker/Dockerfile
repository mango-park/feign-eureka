FROM openjdk:17-jdk-alpine
ADD target/feign-eureka-hello-server-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 7111
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]