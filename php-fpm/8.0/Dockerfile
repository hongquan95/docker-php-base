FROM php:8.0.5-fpm-alpine

LABEL maintainer="Tran Hong Quan <hongquan95.tran@gmail.com>"

# Install composer
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

# Install php ext
RUN docker-php-ext-install pdo pdo_mysql