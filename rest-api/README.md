# api-ittoku-tech

Ruby on Railsフレームワークを使ったREST APIです。

記事の投稿、編集、削除、検索、そして記事に対してのコメントの作成、削除をすることができます。

## 環境構築

APIを動かすには以下のコマンドを実行します。

```bash
docker-compose build
docker-compose up
```

データベースをまだ生成していない場合は以下のコマンドを実行します。

```bash
make db-setup
```

データベースを直に見るには以下のコマンドを実行します。

```bash
make db-access
```

APIのコンテナに入るには以下のコマンドを実行します。

```bash
make api-bash
```

テストを実行するには以下のコマンドを実行します。

```bash
make api-test
```

## Ruby on Rails details

* Ruby version
  * 3.1.2
* System dependencies
  * postgresql
* Configuration
  * ?
* Database creation
  * rails db:setup
* Database initialization
  * rails db:setup
* How to run the test suite
  * rails test
* Services (job queues, cache servers, search engines, etc.)
  * not yet
* Deployment instructions
  * git push origin rails
