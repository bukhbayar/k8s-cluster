FROM node:12.14.1-slim

RUN mkdir /app
WORKDIR /app

COPY k8s-frontend/. ./
RUN npm install
RUN npm run build

EXPOSE 3000

CMD [ "npm", "run", "start" ]