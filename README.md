# ORM PEEWEE KENESH 

## Setting up project

git clone git@github.com:TimaDootaliev/py_24_kenesh_db.git

python3 -m venv venv

. venv/bin/activate

pip install -r requirements-dev.txt

createdb <db_name>

touch .env

fill .env with:
```
USER=
PASSWORD=
HOST=
PORT=
DB_NAME=
```