FROM php:7.1.17-apache

RUN docker-php-ext-install mysqli pdo pdo_mysql

COPY php.ini /usr/local/etc/php/

# Composerが必要なら
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/tmp \
    && mv /tmp/composer.phar /usr/local/bin/composer

# xdebug等を導入する際は以下
# RUN pecl install redis-4.0.1 \
#    && pecl install xdebug-2.6.0 \
#    && docker-php-ext-enable redis xdebug