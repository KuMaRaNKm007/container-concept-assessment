# Use an official MySQL runtime as a parent image
FROM mysql:latest

# Set the root password and create a new database
ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=db

# Copy the database initialization script to the container
COPY ./init.sql /docker-entrypoint-initdb.d/

# Expose the default MySQL port
EXPOSE 3306

