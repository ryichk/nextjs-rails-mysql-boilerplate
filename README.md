# README

## .envファイル作成

.env.sampleをコピーして.envファイルを作成してください。

```sh
cp .env.sample .env
```

.envファイルの下記環境変数の値を設定してください。

- `DB_USERNAME`

- `DB_PASSWORD`

## Docker起動

```ah
docker-compose build
docker-compose up
```

## Run rails setup

```sh
docker-compose exec api bin/setup
```

## CLIでMySQLコンテナに接続

```sh
mysql -u root -p -h localhost -P 3306 --protocol=tcp
```
