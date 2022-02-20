FROM php:8.0-fpm-bullseye

RUN apt update && apt install libicu-dev

RUN docker-php-ext-install pdo_mysql intl
