FROM node:12.14.1-slim

RUN mkdir /app
WORKDIR /app

COPY k8s-api/. ./
RUN npm install
RUN npm run build

CMD [ "npm", "run", "start" ]