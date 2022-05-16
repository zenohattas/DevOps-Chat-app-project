FROM node:latest

WORKDIR /home/node/app

COPY index.js /home/node/app/
COPY package*.json /home/node/app/

RUN npm install

ENV NODE_ENV=production

EXPOSE 3000

CMD [ "node", "index.js" ]