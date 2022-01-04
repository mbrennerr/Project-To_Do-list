FROM mjgargani/puppeteer:trybe1.0 AS todotests
RUN mkdir app
WORKDIR /todo-app/tests/app
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "test" ]
