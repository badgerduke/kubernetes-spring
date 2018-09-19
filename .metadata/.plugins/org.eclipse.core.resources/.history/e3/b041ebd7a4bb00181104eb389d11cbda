FROM openjdk:8u171-jre-alpine3.8
LABEL maintainer="erichamacher@protonmail.com"
COPY . /src
WORKDIR /src
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "service2-0.0.1-SNAPSHOT.jar"]