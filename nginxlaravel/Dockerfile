FROM nginx:stable-alpine

RUN mkdir -p /var/www/html

COPY ./info.php /usr/share/nginx/html/info.php
COPY ./nginx.conf /etc/nginx/conf.d/default.conf


