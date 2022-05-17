FROM node:14-alpine
WORKDIR /home/node/app
COPY ./package*.json ./
RUN npm install
COPY ./ ./
EXPOSE 3000:8888

CMD [ "npm", "start" ]
