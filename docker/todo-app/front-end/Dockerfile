FROM node:14

WORKDIR /app

COPY package.json ./

RUN npm install

EXPOSE 3000

COPY node_modules.tar.gz/ ./

COPY ./ ./

ENTRYPOINT [ "npm" ]

CMD ["start"]