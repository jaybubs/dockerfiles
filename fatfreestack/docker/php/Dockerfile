FROM php:7.4.1-fpm-alpine
RUN docker-php-ext-install pdo pdo_mysql mysqli
RUN apk add --update --no-cache \
bash \
shadow

RUN usermod -u 1000 www-data
