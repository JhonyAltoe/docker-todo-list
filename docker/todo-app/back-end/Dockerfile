FROM node:14-alpine
WORKDIR /home/node/app/back-end
COPY ./package*.json ./
RUN npm install
COPY ./ ./
EXPOSE 3001:8888

CMD [ "npm", "start" ]