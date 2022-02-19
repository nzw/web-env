# Web server on local

## Run server command:
```
$ cp { 初期に作成したいテーブルのSQLファイルのパス } ./docker/db/sql/
$ docker-compose up -d
```

## Stop server command:
```
$ docker-compose stop
```

## Remove server command:
```
$ docker-compose down
$ rm -rf docker/db/data
```

## Home:
```
 * Access the URL: http://localhost:8080
 * Root directory: ./data
```

## Use phpMyAdmin:
```
 * Access the URL: http://localhost:3000/
 * Setting enviroment: ./docker-compose.yml
```
