FROM php:7.4-cli
RUN pecl install xdebug \
    && docker-php-ext-enable xdebug

COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
CMD [ "php", "app.php" ]