
#Specify a base image
FROM node:alpine

WORKDIR /simplenode

#WITH DEFAULT, RE RUN NPM INSTALL IN EVERY CHANGE
# COPY ./ ./ 
# #Install some dependencies
# RUN npm install
#INSTEAD, WE CAN SPLIT DE COPY COMMAND
COPY ./package.json ./
RUN npm install

COPY ./ ./

#EXPOSE 8080
#Default command
CMD ["npm", "start"]