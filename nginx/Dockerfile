FROM nginx:1.25.1-alpine
EXPOSE 80 443
COPY certs/* /etc/nginx/ssl/localhost/
COPY config/nginx.conf /etc/nginx/nginx.conf
