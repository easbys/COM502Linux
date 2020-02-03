FROM php:7-apache
RUN apt update -y
RUN apt install libpng-dev -y
RUN apt install curl -y
RUN apt install libcurl4-openssl-dev -y
RUN docker-php-ext-install pdo pdo_mysql gd curl
RUN a2enmod rewrite
RUN service apache2 restart
