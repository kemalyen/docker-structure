FROM ubuntu/apache2:2.4-20.04_beta

RUN apt-get update && apt-get install vim libapache2-mod-php libapache2-mod-fcgid -y


RUN a2enmod proxy_fcgi setenvif
 
EXPOSE 80