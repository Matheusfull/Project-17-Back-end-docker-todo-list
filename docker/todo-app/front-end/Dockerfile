FROM node:14-alpine

EXPOSE 3000

WORKDIR /user/todo-app/back-end

ADD node_modules.tar.gz ./

COPY . .

CMD ["npm", "start"]
