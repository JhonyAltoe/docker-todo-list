FROM node:14-alpine
WORKDIR /home/node/app/back-end
ADD ./node_modules.tar.gz ./
COPY ./ ./
EXPOSE 3001:8888

CMD [ "npm", "start" ]
