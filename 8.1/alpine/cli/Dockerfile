FROM php:8.1-cli-alpine3.17

RUN apk update && apk add icu-dev

RUN docker-php-ext-install pdo_mysql intl
