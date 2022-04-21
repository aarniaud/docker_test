FROM php:7.3.22-apache

RUN a2enmod rewrite

# Pour que apache pointe directement sur le dossier public
COPY ./apache.conf /etc/apache2/sites-enabled/000-default.conf
