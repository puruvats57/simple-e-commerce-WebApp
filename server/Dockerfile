FROM node:latest

WORKDIR /usr/src/app

COPY ./package.json ./


RUN npm install

COPY . .

EXPOSE 9999

CMD [ "server.js" ]