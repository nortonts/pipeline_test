FROM debian:latest
RUN apt-get update 
RUN apt-get install nginx
RUN rm /etc/nginx/conf.d/default.conf 
COPY nginx.conf /etc/nginx/conf.d/