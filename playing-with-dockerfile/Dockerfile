FROM node:20

WORKDIR /usr/src/app

COPY . .


RUN npm ci

ENV DEBUG=playing-with-dockerfile:* 

CMD npm start
