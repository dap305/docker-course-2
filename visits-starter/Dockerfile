FROM node:14-alpine

WORKDIR /home/app

ADD ./package.json ./
RUN npm install
COPY ./ ./

CMD ["npm", "start"]