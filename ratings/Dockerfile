
FROM node:12.18.1-slim

ENV SERVICE_VERSION="v1"

WORKDIR /home/juansj2000/practica_creativa2/bookinfo/src/ratings

COPY package.json .

RUN npm install

COPY ratings.js .

EXPOSE 9080

CMD ["node","ratings.js","9080"]
