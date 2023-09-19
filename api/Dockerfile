FROM node:20-slim

WORKDIR /api

RUN apt-get update && apt-get upgrade

# nestjsのCLIをインストール
RUN yarn global add @nestjs/cli

COPY . .

# yarn.lockに基づいてパッケージをインストール
RUN yarn install
