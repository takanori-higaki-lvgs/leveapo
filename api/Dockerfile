FROM node:20-slim

WORKDIR /api

# ホストのpackage.jsonとyarn.lockをコンテナの作業ディレクトリにコピー
COPY package.json /api/package.json
COPY yarn.lock /api/yarn.lock

# yarn.lockに基づいてパッケージをインストール
RUN yarn install

# bashのインストール
RUN apk add bash