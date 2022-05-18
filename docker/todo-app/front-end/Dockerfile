FROM node:14-alpine
WORKDIR /home/node/app/front-end
ADD ./node_modules.tar.gz ./
COPY ./ ./
EXPOSE 3000:8888

CMD [ "npm", "start" ]
