FROM php:7.4-alpine3.15

RUN apk update && apk add icu-dev

RUN docker-php-ext-install pdo_mysql intl
