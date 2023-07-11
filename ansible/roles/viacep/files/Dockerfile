FROM nginx:alpine

LABEL description="VIACEP WEBSERVICE"

RUN mkdir -p /var/www/html/site

ENV NGINX_CONF=/etc/nginx/conf.d/default.conf

COPY ./nginx.conf $NGINX_CONF

COPY ./index.html /var/www/html/site

EXPOSE 80
