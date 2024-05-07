FROM node:18-alpine

WORKDIR /app/products

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3002

CMD [ "npm","start" ]