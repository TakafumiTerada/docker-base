FROM php:7.4-fpm

RUN apt-get update -y
RUN apt-get install -y zip unzip

RUN curl -sS https://getcomposer.org/installer | php
RUN mv composer.phar /usr/local/bin/composer
