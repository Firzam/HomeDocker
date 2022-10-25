FROM php:7.0-apache

RUN apt-get -y update
RUN apt-get -y upgrade
RUN apt-get -y install libpq-dev libpq5
RUN docker-php-ext-install pdo pdo_pgsql

RUN mv $PHP_INI_DIR/php.ini-production $PHP_INI_DIR/php.ini
RUN sed -i "s/;extension=php_pdo_pgsql.dll/extension=php_pdo_pgsql.dll/g" $PHP_INI_DIR/php.ini