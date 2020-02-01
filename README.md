# Setup

当リポジトリをクローンしたディレクトリまで移動
```
$ cd glucose_sensors
```

初回はイメージをビルドする（Dockfileを編集したときも同様）
```
$ docker-compose build
```

コンテナの起動
```
$ docker-compose up -d
```

インスタンスの起動に成功したら9050番ポートからアクセス可能

http://localhost:9050/


## Webサーバーへのログイン
インスタンス起動後に以下のコマンドを実行

```
$ docker exec -it gs_web bash
```
