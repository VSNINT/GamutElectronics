# Use the official Apache image from Docker Hub
FROM httpd:2.4

# Copy static website files to Apache's document root
COPY . /usr/local/apache2/htdocs/

# Ensure Apache config is set up correctly
RUN echo "LoadModule mpm_event_module modules/mod_mpm_event.so" >> /usr/local/apache2/conf/httpd.conf
RUN echo "DirectoryIndex index.html" >> /usr/local/apache2/conf/httpd.conf

# Expose port 80
EXPOSE 80




