FROM node:lts-alpine

WORKDIR /var/www/html/vueproje

COPY package*.json ./

RUN npm install

CMD ["npm", "run", "build"]