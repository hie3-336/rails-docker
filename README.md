# 環境構築の方法

このRailsプロジェクトはDocker化されております。
実行するためには以下の手順を行ってください。

1 git cloneを実行する

以下のようにターミナルでgit cloneを実行し、必要なファイルをすべてcloneしてください。

```
$ git clone https://github.com/hie3-336/rails-docker
```

2 作業フォルダに移動する

Railsプロジェクトのディレクトリに移動してください。
```
$ cd rails-docker
```

3 dockerをbuildする
dockerのimageをビルドします。
```
$ docker-compose build
```

4 コンテナを作成して起動する
コンテナをデタッチモードで作成・起動します。
```
$ docker-compose up -d
```

以上で環境構築が完了します。
ブラウザで　http://localhost:3000　にアクセスすると、タスク管理のデモアプリが起動します。確認をしてみてください。

# アプリの停止方法
コンテナを停止するためにはdownのコマンドを使用してください。

```
$ docker-compose down
```
