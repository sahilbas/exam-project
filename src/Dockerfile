
FROM php:8.1-apache

RUN apt-get update && docker-php-ext-install mysqli pdo && docker-php-ext-enable mysqli pdo

COPY . /var/www/html/
# Install PHP extensions
#RUN docker-php-ext-install mysqli pdo pdo_mysql

# # Copy PHP files into container
# WORKDIR /var/www/html/

# RUN apt-get update -y && apt-get install -y libmariadb-dev


# Start Apache service
#CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
