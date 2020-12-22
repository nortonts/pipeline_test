FROM node:11.1.0-alpine

WORKDIR /home/node

COPY . .

RUN npm install

CMD npm start

FROM nginx:1.19.0-alpine 
RUN rm /etc/nginx/conf.d/default.conf 
COPY nginx.conf /etc/nginx/conf.d