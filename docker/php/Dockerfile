FROM php:7.4-fpm

WORKDIR /var/www/test.loc

# этот тег для комитирование
RUN apt-get update && apt-get install -y \
    && docker-php-ext-install pdo_mysql

# установка xdebug. Узнать версию тут https://xdebug.org/
RUN pecl install xdebug-2.9.1 \
    && docker-php-ext-enable xdebug


