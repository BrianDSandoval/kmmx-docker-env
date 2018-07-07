FROM php:7.2-apache
ENV DEBIAN_FRONTEND noninteractive
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli
RUN a2enmod rewrite