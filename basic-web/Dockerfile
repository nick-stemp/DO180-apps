FROM registry.redhat.io/ubi8/ubi:latest
MAINTAINER Nick <nick@frolha.com>
LABEL description="A simple web server container from source"
RUN yum update && yum install -y httpd && yum clean all
COPY ./html/ /var/www/html/
RUN echo $(date) >> /var/www/html/index.html
EXPOSE 80
ENTRYPOINT ["httpd", "-D", "FOREGROUND"]
 
