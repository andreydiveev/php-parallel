FROM php:7.4-zts-buster

RUN pecl install parallel
RUN echo "extension=parallel.so" > /usr/local/etc/php/conf.d/parallel.ini
