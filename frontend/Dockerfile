FROM node:20-alpine

WORKDIR /src

COPY package*.json ./

RUN npm install

COPY . .


EXPOSE 8081


CMD ["npx", "ng", "serve", "--host", "0.0.0.0", "--port", "8081"]
