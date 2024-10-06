# Basae Image
FROM php:8.3.12-fpm-alpine

# Install Dependency
RUN docker-php-ext-install pdo_mysql mysqli bcmath

#Set Working DIR
WORKDIR /var/www/html

#Expose Port
EXPOSE 9000