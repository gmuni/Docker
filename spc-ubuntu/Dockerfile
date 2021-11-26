FROM ubuntu:18.04
RUN apt update
RUN apt install openjdk-8-jdk -y
RUN wget https://testbucketawsgroup1.s3.amazonaws.com/spring-petclinic-2.5.0-SNAPSHOT.jar
EXPOSE 8080
CMD ["java", "-jar", "spring-petclinic-2.5.0-SNAPSHOT.jar"]