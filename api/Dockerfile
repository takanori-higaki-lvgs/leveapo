FROM node:20-slim

WORKDIR /api

RUN apt-get update && apt-get upgrade

COPY . .

# yarn.lockに基づいてパッケージをインストール
RUN yarn install
