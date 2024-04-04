FROM openjdk:17-jdk-alpine
ADD target/feign-eureka-hello-client-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 7211
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]