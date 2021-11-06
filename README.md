## DOCKER練習リポジトリ

アプリの起動 (バックグラウンド)
＄ docker-compose up
($ docker-compose up -d)

アプリの停止
＄ docker-compose down

rails new (docker)
$ docker-compose run --no-deps web rails new . --force --database=postgresql
