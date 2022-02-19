FROM php:7.3.33-fpm

RUN apt-get update \
    && docker-php-ext-install pdo_mysql
RUN apt-get update && docker-php-ext-install mysqli && docker-php-ext-enable mysqli