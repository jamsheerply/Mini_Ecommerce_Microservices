FROM node:18-alpine

WORKDIR /app/shopping

COPY package.json .


RUN npm install


COPY . .

EXPOSE 3003

CMD [ "npm","start" ]