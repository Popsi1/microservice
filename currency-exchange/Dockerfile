# define base docker image, ur base image jdk must me higher that the app jdk
FROM openjdk:21
LABEL maintainer="steven"
ADD target/currency-exchange-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar", "app.jar"]