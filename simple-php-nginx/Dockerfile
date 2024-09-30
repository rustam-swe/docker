# Start by using a PHP image that already has PHP-FPM (FastCGI Process Manager) installed.
FROM php:8.1-fpm

# Copy our PHP files from our computer into the Docker container.
COPY ./public /var/www/html

# Set the directory where PHP will look for files to run.
WORKDIR /var/www/html
