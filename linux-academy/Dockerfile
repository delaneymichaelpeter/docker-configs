# This image is based on CentOS 7 and will start apache service in each container

# Image based on
FROM centos:latest
MAINTAINER Peter Delaney delaneymichaelpeter@gmail.com

# Add new user to environment
RUN yum update -y
RUN yum install -y httpd net-tools

RUN echo "This is a custom index file build during image creation:" > /var/www/html/index.html

EXPOSE 80

ENTRYPOINT apachectl "-DFOREGROUND" 








