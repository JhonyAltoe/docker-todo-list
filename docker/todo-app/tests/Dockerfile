FROM mjgargani/puppeteer:trybe1.0
WORKDIR /home/node/app/tests
ADD ./node_modules.tar.gz ./
COPY ./ ./

CMD [ "npm", "test" ]
