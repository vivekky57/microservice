#Start with the base image containing Java runtime
FROM eclipse-temurin:21-jdk-alpine
#Information around who maintains the image
LABEL maintainer="vivek"
#Add the application jar's to the image
COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar
# excute the application
ENTRYPOINT ["java","-jar","accounts-0.0.1-SNAPSHOT.jar"]