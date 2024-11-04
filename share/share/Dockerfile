# Use the official Apache image from the Docker Hub
FROM httpd:2.4

# Copy static website files to Apache's document root
COPY . /usr/local/apache2/htdocs/

# Ensure index.html is correctly exposed and prioritized
RUN echo "DirectoryIndex index.html" > /usr/local/apache2/conf/httpd.conf

# Expose port 80
EXPOSE 80



