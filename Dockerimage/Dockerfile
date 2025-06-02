FROM httpd:2.4

# Copy the custom configuration file into the container
COPY neogym-html /usr/local/apache2/htdocs/

# working directory
WORKDIR /usr/local/apache2/htdocs/

# Expose port 80
EXPOSE 80