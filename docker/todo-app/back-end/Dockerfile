#FROM node:14

#WORKDIR /usr/src/app

#COPY package*.json ./

#ADD node_modules.tar.gz .

#RUN npm install

#COPY . .

#EXPOSE 3001

#CMD [ "npm", "start" ]

FROM node:14-alpine

EXPOSE 3001

WORKDIR /user/todo-app/back-end

ADD node_modules.tar.gz ./

COPY . .

CMD ["npm", "start"]