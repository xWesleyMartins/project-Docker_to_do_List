FROM node:14

WORKDIR /todo-app/front-end

EXPOSE 3000

ADD node_modules.tar.gz ./

COPY . .

RUN npm install

ENTRYPOINT [ "npm" ]

CMD [ "start" ]
