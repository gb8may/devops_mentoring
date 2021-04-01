FROM ubuntu

LABEL version="1.0" description="Nginx with Docker" maintainer="Mayara Gouveia"

RUN apt update

RUN apt install nginx -y

EXPOSE 80

COPY index.html /var/www/html

CMD ["nginx","-g","daemon off;"]
