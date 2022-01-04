FROM node:14-alpine AS todobackend

RUN mkdir app
WORKDIR /todo-app/back-end/app
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3001
ENTRYPOINT [ "npm", "start" ]
