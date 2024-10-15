FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY packages/package*.json ./

COPY src/ ./

EXPOSE 3032

RUN npm install

ENTRYPOINT ["node", "main.js"]