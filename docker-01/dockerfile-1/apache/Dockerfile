# Base Image. 

FROM ubuntu:16.04 



# Update the Repo. 

RUN apt-get update



# Install Apache Packages

RUN apt-get install apache2 -y 



# Custom Index html. 

COPY info.html /var/www/html/info.html 



# Exposing the service on the following Port

EXPOSE 8080



# Starting the Apache Service 

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
