FROM node:14-alpine AS todobackend

RUN mkdir app
WORKDIR /todo-app/front-end/app
ADD node_modules.tar.gz .
COPY . .
EXPOSE 3000
ENTRYPOINT [ "npm", "start" ]