FROM node:14.17

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install npm -g
RUN npm install

EXPOSE 8081

CMD ["yarn", "start"]