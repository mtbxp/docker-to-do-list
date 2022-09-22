FROM mjgargani/puppeteer:trybe1.0

ADD ./node_modules.tar.gz .

WORKDIR /todotests

COPY . .

RUN npm install

CMD ["npm", "test"]
