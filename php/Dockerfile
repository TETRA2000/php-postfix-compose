FROM php:5.6-apache

RUN apt-get update && apt-get install -y ssmtp && rm -rf /var/lib/apt/lists/*

COPY php.ini /usr/local/etc/php/php.ini
COPY ssmtp.conf /etc/ssmtp/ssmtp.conf
