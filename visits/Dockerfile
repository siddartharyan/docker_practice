FROM node:alpine
WORKDIR /usr/app/node_redis
COPY ./package.json ./
RUN npm install
COPY ./ ./
CMD ["npm","start"]