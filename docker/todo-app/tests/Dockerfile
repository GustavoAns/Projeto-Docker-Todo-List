FROM mjgargani/puppeteer:trybe1.0 as todotests
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
RUN npm install
CMD [ "npm", "test" ]
