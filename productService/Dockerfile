FROM node:16-alpine
WORKDIR /app
COPY productService/package*.json ./

RUN npm install
# If you are building your code for production
# RUN npm ci --only=production



EXPOSE 8081

CMD [ "node", "server.js" ]
