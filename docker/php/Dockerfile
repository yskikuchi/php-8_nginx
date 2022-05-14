FROM php:8.0-fpm

# COPY php.ini
COPY ./docker/php/php.ini /usr/local/etc/php/php.ini

RUN apt-get update && \
    apt-get -y install \
    git \
    zip \
    unzip \
    vim \