# server/Dockerfile
FROM node:14

WORKDIR /usr/src/app

COPY package*.json ./
RUN npm install

COPY . .

COPY .env .env

EXPOSE 5001
CMD ["npm", "start"]
