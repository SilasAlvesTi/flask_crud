# Flask_crud

Experiência com um crud usando flask e suas ferramentas

- Flask
- flask_sqlalchemy
- flask_migrate
- flask_marshmallow
- marshmallow_sqlalchemy

## Como rodar esse app

```sh
export FLASK_APP=app
export FLASK_ENV=Development
export FLASK_DEBBUG=True

flask run
```

## Como fazer as migrações

```sh
flask db init
flask db migrate
flask db upgrade
```