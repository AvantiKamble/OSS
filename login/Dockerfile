FROM node:7
WORKDIR /app
COPY package.json /app
RUN npm install 
COPY . /app
CMD node login.js
EXPOSE 9000