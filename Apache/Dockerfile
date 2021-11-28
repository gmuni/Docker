FROM ubuntu:18.04
LABEL author="Munichandra"
LABEL organization="TR"
RUN apt update && apt-get install apache2 -y
EXPOSE 80
CMD ["apache2ctl", "-D", "FOREGROUND"]