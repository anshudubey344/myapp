FROM wordpress:latest

# Copy the custom theme into the WordPress themes directory
COPY ./wp-content/themes/my-theme /var/www/html/wp-content/themes/my-theme

# Set file permissions
RUN chown -R www-data:www-data /var/www/html/wp-content/themes/my-theme

