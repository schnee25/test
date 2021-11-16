# 「Wonder Scrum」

## 概要

WonderScrum 専用のボイラープレート Rails6（REST API）+ Docker + PostgreSQL + Graphql

## 開発環境構築

### 環境構築する手順

1. .env ファイルを作成
2. .env.sample の中身を.env ファイルにコピペする
3. DATABASE_NAME=example_development を DATABASE_NAME=wonder-scrum_development に変更する
4. database.yml の[example]を wonder-scrum に変更する
5. docker-compose up -d --build コマンドを叩いて、完了

ルビーわかんない！
