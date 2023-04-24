## Install

```shell
$ cp .env.example .env
$ poetry install
```

And edit `.env` file.

# Migrate database

```shell
$ poetry run ./manage.py migrate
```

# Initialize tailwind cli

```shell
poetry run ./manage.py tailwind installcli
```

# Start tailwind server

```shell
$ poetry run ./manage.py tailwind watch
```

# Start dev server
```shell
$ poetry run ./manage.py runserver
```
