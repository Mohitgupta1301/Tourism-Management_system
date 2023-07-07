# Use a PHP base image
FROM php:7.4-apache
RUN docker-php-ext-install mysqli pdo pdo_mysql

# Set the working directory
WORKDIR /var/www/html

# Copy the frontend files to the container
COPY . /var/www/html

# Expose the port on which the frontend will run
EXPOSE 80

# Start the PHP development server
CMD ["apache2-foreground"]
