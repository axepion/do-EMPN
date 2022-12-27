FROM php:7.4-fpm

ADD php-composer.sh /var/project/backend 

WORKDIR /var/project/backend

RUN apt-get update && apt-get install -y \
&& docker-php-ext-install pdo mysqlii \
&& chmod +x php-composer.sh \
&& ./php-composer.sh
