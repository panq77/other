FROM openjdk:8-jdk-alpine
VOLUME /tmp
ADD share-0.6.0-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]