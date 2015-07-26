FROM nginx:latest

ADD nginx.conf /etc/nginx/nginx.conf
ADD registry.conf /etc/nginx/conf.d/registry.conf
RUN mkdir /certs
ADD /certs /certs
