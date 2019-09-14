FROM node:slim

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install
RUN npm audit fix

COPY . ./

CMD ["node", "index.js"]

EXPOSE 3000