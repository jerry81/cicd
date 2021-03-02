FROM node:14-buster-slim

WORKDIR /app

COPY . .

RUN yarn config set registry 'https://registry.npm.taobao.org'
RUN yarn && yarn build

# CMD yarn start
