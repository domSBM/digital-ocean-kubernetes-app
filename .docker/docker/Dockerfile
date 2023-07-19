FROM php:8.0-apache

#Install php mysql extension
RUN docker-php-ext-install mysqli

#Enable apache rewrite module
RUN a2enmod rewrite 

#Install php debugger
RUN pecl install xdebug-3.0.0