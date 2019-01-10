# Version 1.0

FROM ubuntu:16.04
MAINTAINER Jonathan Simanca  "jsimanca@grupodot.com"
RUN apt-get update && apt-get install -y nginx && \
echo "\ndaemon off;" >> /etc/nginx/nginx.conf
WORKDIR /var/www/html
COPY . .
CMD ["nginx"]
EXPOSE 80