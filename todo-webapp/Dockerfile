FROM node:alpine

COPY . /root/todo-webapp
WORKDIR /root/todo-webapp
RUN yarn install

EXPOSE 3000
CMD  yarn start
