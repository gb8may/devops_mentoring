FROM ubuntu
RUN apt-get update
RUN apt-get install nginx -y
COPY index.html /var/www/html/
EXPOSE 80
CMD ["nginx","-g","daemon off;"]
LABEL version="1.0.0" description="Subindo site com Nginx e Docker" maintainer="Wellington Costa<fcowellcosta@gmail.com>"
