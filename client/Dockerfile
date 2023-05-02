FROM node:13.12-alpine

RUN mkdir -p client

WORKDIR /client

COPY . /client

RUN npm install

CMD [ "npm", "start" ]