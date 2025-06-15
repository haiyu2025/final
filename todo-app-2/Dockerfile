FROM docker-0.unsee.tech/node:18-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8081
CMD [ "npm", "start" ]