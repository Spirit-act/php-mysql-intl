FROM php:8.2-fpm-alpine3.17

RUN apk update && apk add icu-dev

RUN docker-php-ext-install pdo_mysql intl
