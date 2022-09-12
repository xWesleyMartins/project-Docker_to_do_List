FROM node:14

WORKDIR /back-end

EXPOSE 3001

ADD node_modules.tar.gz ./

COPY . .

RUN npm install

ENTRYPOINT ["npm", "start"]