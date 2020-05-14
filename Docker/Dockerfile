FROM registry.access.redhat.com/ubi7
RUN yum install -y httpd
COPY index.html /var/www/html/
EXPOSE 80
USER root
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
