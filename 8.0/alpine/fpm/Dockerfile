FROM php:8.0-fpm-alpine3.16

RUN apk update && apk add icu-dev

RUN docker-php-ext-install pdo_mysql intl
