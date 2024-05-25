FROM node:18-alpine

WORKDIR /app

COPY package.json .

RUN npm i

COPY . .

RUN npm run build

RUN rm -fr node_modules