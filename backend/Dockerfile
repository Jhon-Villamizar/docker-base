FROM node:18

WORKDIR /

COPY package*.json ./

RUN yarn

COPY . .

EXPOSE 3000

CMD ["yarn", "start:dev"]
