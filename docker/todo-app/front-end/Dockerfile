FROM node:14-alpine as todofrontend
EXPOSE 3000
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
RUN npm install
CMD [ "npm", "start" ]
