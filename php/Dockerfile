FROM php:apache

WORKDIR /var/www/html
RUN docker-php-ext-install mysqli && docker-php-ext-enable mysqli

COPY index.php/ /var/www/html/
COPY footer.php/ /var/www/html/
COPY header.php/ /var/www/html/
COPY common.php/ /var/www/html/
COPY config.php/ /var/www/html/
COPY create.php/ /var/www/html/
COPY delete.php/ /var/www/html/
COPY install.php/ /var/www/html/
COPY read.php/ /var/www/html/
COPY style.css/ /var/www/html/
COPY update.php/ /var/www/html/
COPY update-single.php/ /var/www/html/