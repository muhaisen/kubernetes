FROM node:21.6.0-alpine3.19

WORKDIR /src

COPY package*.json .

RUN npm install

COPY . .

CMD [ "node",  "server.js" ]