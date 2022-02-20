FROM php:7.4-fpm-bullseye

RUN apt update && apt install -y libicu-dev

RUN docker-php-ext-install pdo_mysql intl
