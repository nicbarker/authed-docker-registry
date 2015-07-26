FROM nginx:latest

ADD nginx/nginx.conf /etc/nginx/nginx.conf
ADD nginx/registry.conf /etc/nginx/conf.d/registry.conf
RUN mkdir /certs
ADD certs /certs
