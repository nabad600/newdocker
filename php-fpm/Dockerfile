FROM php:fpm-alpine

RUN apk add --no-cache bash
RUN docker-php-ext-install pdo_mysql

CMD ["php-fpm"]

EXPOSE 9000