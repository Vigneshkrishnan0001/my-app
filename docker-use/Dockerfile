FROM node:alpine

#Specify a working directory
WORKDIR /usr/app

#Copy the dependencies file
COPY ./package.json ./

#Install 
RUN npm install 

#Copy remaining files
COPY ./ ./

#Default command
CMD ["npm","start"]
