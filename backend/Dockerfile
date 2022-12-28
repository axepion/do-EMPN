FROM php:7.4-fpm

WORKDIR /var/project/backend

COPY . .

RUN chmod +x php-composer.sh \
&&./php-composer.sh
