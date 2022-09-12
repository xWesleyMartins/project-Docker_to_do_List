FROM node:14

WORKDIR /tests

ADD node_modules.tar.gz ./

COPY . .

RUN npm install

ENTRYPOINT ["npm", "test"]
