FROM node:20-slim

WORKDIR /front

RUN apt-get update && apt-get upgrade

# nestjsのCLIをインストール
RUN npm i -g @nestjs/cli

COPY . .

# yarn.lockに基づいてパッケージをインストール
RUN yarn install
