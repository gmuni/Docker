FROM openjdk:8
# base image is openjdk
LABEL author="Munichandra"
LABEL maintainer="login4munichandra@gmail.com"
ENV applicationpath='/springpetclinic.jar'
ENV dummy='dummy'
ARG downloadlocation
# Downloading the image from the url
ADD  ${downloadlocation} ${applicationpath}
# spring pet clinic runs on port 8080
EXPOSE 8080
# command to start the application
CMD ["java",  "-jar",  ${applicationpath} ]

# Here downloading location we will give through commandline like below
#docker image build -t envargdemo:1.0 --build-arg downloadlocation='https://testbucketawsgroup1.s3.amazonaws.com/spring-petclinic-2.5.0-SNAPSHOT.jar' .