FROM node:16-alpine

WORKDIR /app
COPY customerService/package*.json ./

RUN npm install

EXPOSE 8080

CMD [ "node", "server.js" ]
