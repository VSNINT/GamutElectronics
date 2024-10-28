# Use an official Nginx image to serve the static website
# Use the official Apache image from the Docker Hub
FROM httpd:2.4

# Copy your static website files to the Apache document root
COPY ./public-html/ /usr/local/apache2/htdocs/

# Expose port 80 to the outside world
EXPOSE 80

