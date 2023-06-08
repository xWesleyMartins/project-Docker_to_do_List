FROM node:14

WORKDIR /todo-app/tests

ADD node_modules.tar.gz ./

COPY . .

RUN npm install

ENTRYPOINT [ "npm" ]

CMD [ "test" ]