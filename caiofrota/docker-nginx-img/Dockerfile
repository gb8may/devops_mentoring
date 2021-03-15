############################################################
# Dockerfile to build Nginx Installed Containers
# Based on Ubuntu
############################################################

# Set base image.
FROM ubuntu

# Label.
LABEL version="1.0.0" description="Nginx Server" maintainer="Caio Frota<caiofrota@gmail.com>"

# Install NGINX.
RUN apt-get update
RUN apt-get install -y nginx

# Copy files.
COPY src/ /var/www/html/

# Expose ports.
EXPOSE 80

# Default command to execute when creating a new container.
CMD ["nginx", "-g", "daemon off;"]
