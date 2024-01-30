FROM ubuntu
RUN apt-get update
RUN apt-get install -y nginx
COPY . /var/www/html
EXPOSE 80
EXPOSE 443
ENTRYPOINT [ "/usr/sbin/nginx", "-g", "daemon off;" ]