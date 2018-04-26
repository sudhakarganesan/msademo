FROM openjdk:8-jdk-alpine
VOLUME /tmp
COPY demo1.0.jar demo1.0.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/demo1.0.jar"]