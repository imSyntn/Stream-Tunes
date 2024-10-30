FROM node:22-alpine

WORKDIR /Server

COPY /package*.json .

RUN npm i

COPY . .

EXPOSE 8000:8000

CMD [ "npm", "run", "dev" ]