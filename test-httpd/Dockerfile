# My dockerfile of a web server with time
FROM registry.redhat.io/rhel8/httpd-24:latest
LABEL description="My custom httpd container image"
MAINTAINER Nick S <nick@frolha.com>
EXPOSE 8080
COPY ./html/ /var/www/html/
#ENTRYPOINT ["/usr/bin/httpd"]
# CMD ["mkdir /var/www/html", "echo $(date) >> /var/www/html/index.html"]

