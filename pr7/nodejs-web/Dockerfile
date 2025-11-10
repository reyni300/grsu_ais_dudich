FROM node:18

#Create app directory
WORKDIR /usr/src/app

#Install app dependecies
COPY package*.json ./
RUN npm install

#Budle app source
COPY . .

EXPOSE 8080
CMD [ "node", "server.js" ]
