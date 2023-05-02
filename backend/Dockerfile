FROM node:13.12-alpine 

RUN mkdir -p backend

WORKDIR /backend

COPY . /backend

RUN npm install

CMD [ "npm", "start" ]
