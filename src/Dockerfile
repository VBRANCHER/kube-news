FROM node:16.18.0
WORKDIR /app
COPY package*.json ./
RUM npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]