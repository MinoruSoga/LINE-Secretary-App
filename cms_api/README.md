# プロジェクト

公式LINE CMS

# DBの永続化
```
$ docker volume create line-db_volume
```

# コンテナ起動
```
$ make up 
```

# migration
```
$ make migrate-up
```