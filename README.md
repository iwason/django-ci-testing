# django-docker


### 作成する環境
- Python 3.9.6
- PostgreSQL 13.4
- nginx 1.20.1

### サービスの構築
```
$ docker compose build
```

### Djangoインストールコマンド
```
$ docker compose exec app django-admin.py startproject app .
```

### Django テスト実行
```
$ docker compose exec app ./manage.py test
```
