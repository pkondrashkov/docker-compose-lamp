FROM php:7-apache

RUN apt-get update -y && apt-get install -y libpng-dev

RUN docker-php-ext-install pdo pdo_mysql gd