FROM node:14

EXPOSE 3001

ADD node_modules.tar.gz .

COPY . ./docker/todo-app/back-end/Dockerfile

CMD [ "npm start" ]