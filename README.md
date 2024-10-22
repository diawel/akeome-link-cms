# virtual-gallery-cms

## ローカルでの動かし方

### 1. 環境変数の設定

```
$ cp .env.example .env
```

適宜、`.env` の内容を書き換える（ローカルでは基本的に書き換え不要）。

### 2. コンテナの起動

Docker が起動していることを確かめた上で、以下のコマンドを実行。

```
$ docker compose up -d
```

### 3. コンテナの停止

```
$ docker compose down
```
