FROM node:6

RUN npm install -g gulp

WORKDIR /var/www/laravel
CMD npm install && gulp watch

EXPOSE 3000
EXPOSE 3001
