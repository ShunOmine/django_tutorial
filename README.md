## 環境構築
`pip install --upgrade pip`

`pip install -r requirements.txt`

## DB
`python manage.py migrate`

`python manage.py migrate blog`

## サーバー起動
`python manage.py runserver`

URL:  `localhost:8000`

## Dir構造
```
djnago_tutorial/
  .gitignore
  db.sqlite3
  manage.py
  READEME.md
  requirements.txt
  blog/
    migrations/
      0001_initial.py
      __init__.py
    __init.py
    admin.py
    apps.py
    models.py
    tests.py
    views.py
  mysite/
    __init__.py
    settings.py
    urls.py
    wsgi.py 
```
