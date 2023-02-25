FROM node:18-alpine

WORKDIR /usr/src/app

COPY . . 

RUN npm install --production

CMD ["node" , "server.js"]

EXPOSE 5000


