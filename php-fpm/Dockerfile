FROM php:fpm-alpine

RUN docker-php-ext-install pdo_mysql

CMD ["/bin/bash","php-fpm"]

EXPOSE 9000