FROM php:7.1.8-apache

MAINTAINER Willian Maria

COPY . /var/www/app
COPY vhost.conf /etc/apache2/sites-available/000-default.conf

RUN chown -R www-data:www-data /var/www/app && a2enmod rewrite