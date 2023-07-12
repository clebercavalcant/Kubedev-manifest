FROM node:18.16-buster-slim
WORKDIR /app
COPY package*.json ./
RUN apt update && \
    npm install
COPY . .
EXPOSE 8080
CMD [ "node", "server.js" ]