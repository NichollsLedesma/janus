FROM php:8.0.3-fpm

# Set working directory
WORKDIR /var/www

# Install dependencies
RUN apt-get update

# Clear cache
RUN apt-get clean && rm -rf /var/lib/apt/lists/*

EXPOSE 9000

CMD ["php-fpm"]