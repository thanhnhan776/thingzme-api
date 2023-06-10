# ThingzMe API - django project

## 1. Start database service

- Create `mysql.cnf` config file:

```
[client]
host = <host - 0.0.0.0>
database = <db-name>
user = <db-user>
password = <db-pass>
default-character-set = utf8
```

- Run command:

```
> docker-compose up -d
```

## 2. Start project

- Create and activate python virtual environment.
- Install dependencies:

```
> pip3 install -r requirements.txt
```

- Run command:

```
> python3 manage.py runserver
```
