# Usa una imagen base de Node.js para construir la aplicación
FROM node:14 AS build

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]