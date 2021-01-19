FROM debian:latest
RUN apt-get update && apt-get install -y nginx
COPY nginx.conf /etc/nginx/conf.d
CMD ["nginx", "-g", "daemon off;"]