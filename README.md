## DOCKER 練習リポジトリ

### アプリの起動 (バックグラウンド)

＄ docker-compose up  
($ docker-compose up -d)

### アプリの停止

＄ docker-compose down

### rails new (docker)

$ docker-compose run --no-deps web rails new . --force --database=postgresql

### コンテナの確認

動作中 $ docker ps  
停止中 $ docker ps -a

### コンテナの削除

$ docker rm 　 ID

### イメージの確認

$ docker images

### イメージの削除

$ docker rmi ID
