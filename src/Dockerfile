FROM node:22-alpine

WORKDIR /app

COPY public . 

COPY packdddddage.json .

RUN yarn install

COPY . .

EXPOSE 3000

CMD [ "node", "server.js" ]
