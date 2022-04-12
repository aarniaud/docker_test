FROM php:7.3.22-apache

RUN chmod -R 733 .

#RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
#RUN apt-get update && apt-get upgrade -y

# Pour que apache pointe directement sur le dossier public
COPY ./apache.conf /etc/apache2/sites-enabled/000-default.conf
