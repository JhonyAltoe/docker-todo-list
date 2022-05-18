FROM mjgargani/puppeteer:trybe1.0
WORKDIR /home/node/app/tests
COPY ./package*.json ./
RUN npm install
COPY ./ ./
EXPOSE 3000

CMD [ "npm", "test" ]