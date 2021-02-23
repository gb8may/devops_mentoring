FROM ubuntu

LABEL version="1.0" description="Nginx with Docker" maintainer="Lucas Soeiro<n3x4m0s@gmail.com>"

RUN apt update

RUN apt install nginx -y

EXPOSE 80

COPY index.html /var/www/html

CMD ["nginx","-g","daemon off;"]
