FROM node:14-alpine

EXPOSE 3000

ADD node_modules.tar.gz .

WORKDIR /front-end/

COPY . .

RUN npm install

ENTRYPOINT [ "npm", "start" ]
