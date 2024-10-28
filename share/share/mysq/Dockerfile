# Use the official MySQL image
FROM mysql:latest

# Set environment variables for root password, database, user, and user password
ENV MYSQL_ROOT_PASSWORD=root_password
ENV MYSQL_DATABASE=my_database
ENV MYSQL_USER=my_user
ENV MYSQL_PASSWORD=my_password

# Expose the MySQL port
EXPOSE 3306

# Start MySQL server
CMD ["mysqld"]

