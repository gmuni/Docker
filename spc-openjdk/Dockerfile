FROM openjdk:8
# base image is openjdk
LABEL author="Munichandra"
LABEL maintainer="login4munichandra@gmail.com"
# Downloading the image from the url
ADD https://testbucketawsgroup1.s3.amazonaws.com/spring-petclinic-2.5.0-SNAPSHOT.jar /spring-petclinic.jar
# spring pet clinic runs on port 8080
EXPOSE 8080
# command to start the application
CMD ["java", "-jar", "/spring-petclinic.jar"]