FROM node:14-alpine

EXPOSE 3001

ADD ./node_modules.tar.gz .

WORKDIR /todobackend

COPY . .

RUN npm install

CMD ["npm", "start"]
