
FROM node:alpine as builder

COPY package.json .
COPY package-lock.json .
RUN npm install --force
COPY . .
RUN npm run build
 
EXPOSE 3000

