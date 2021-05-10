FROM centos
MAINTAINER father <father@gmail.com>
RUN yum install git httpd -y
RUN git clone https://github.com/venkatareddybandi9999/game--java.git /var/www/html
CMD ["httpd " , "-DFOREGROUND"]

