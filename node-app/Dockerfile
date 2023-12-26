FROM node:alpine

WORKDIR /app
ADD index.js /app
ADD package.json /app

RUN npm install

CMD ["node", "/app/index.js"]
