# Patch 1 - Bread

This assumes you have pipenv setup. Look [here](https://github.com/pypa/pipenv) for setup instructions.

## How to run tests

```bash
pipenv install -d
pipenv shell
pip install -e app/

./test
```

## How to run the server

```bash
export FLAG=123
export FLAG_SECRET=123
export DB_CONNECT_STRING='some/path/so/a/sqlite3/db/you/have/created'
python3 run.py
```