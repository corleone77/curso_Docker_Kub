 #Image
 #Modificacion de la imagen alpine por node:alpine
 FROM node:alpine


WORKDIR /usr/app 
#RUN command to execute
COPY ./package.json ./
RUN npm install 
#RUN apk add --update nodejs
COPY ./ ./


CMD ["npm", "start"]

