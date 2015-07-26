FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf
COPY registry.conf /etc/nginx/conf.d/registry.conf
RUN mkdir /certs
ADD /certs /certs
