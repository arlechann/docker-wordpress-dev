FROM wordpress:5.5-php7.4-apache

COPY ./custom.ini /custom.ini
RUN mv /custom.ini ${PHP_INI_DIR}/conf.d
