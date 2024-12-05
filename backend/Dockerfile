FROM node:20-latest

ADD . /app
WORKDIR /app

RUN npm i --omit=dev

EXPOSE 23000

USER node
CMD npm run start