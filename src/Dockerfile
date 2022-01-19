FROM node:16.13.2-alpine3.15
LABEL name: <Conversão de Temperatura>
LABEL version: <1.0>
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
