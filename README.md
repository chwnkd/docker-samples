# docker-samples

## ml-base

1. ディレクトリ移動

```
$ cd ml-base/
```

2. コンテナ起動

```
$ docker-compose up -d
```

3. JupyterのWebアクセス情報取得

```
$ docker-compose exec ml-base jupyter notebook list
```

`http://0.0.0.0:8888/xxxxxxx` と表示されるので、
`http://localhost:9088/xxxxxxx` にしてアクセス。
