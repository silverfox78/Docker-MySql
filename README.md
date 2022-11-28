# MY-SQL

## TL:DR

> https://samuelbarrerabastidas.medium.com/mysql-con-docker-compose-1c980e966e17

## Imagenes oficiales de MySql

> https://hub.docker.com/_/mysql

## Repositorio Local

> https://github.com/silverfox78/Docker-MySql.git

```sh
git init
git add .
git commit -am "Docker-Compose Mysql || Ejemplo practico"
git remote add origin https://github.com/silverfox78/Docker-MySql.git
git pull --rebase origin main
git push -u -f origin main
```

## Identificacion

| Dato      | Valor     |
| --------- | --------- |
| hostname  | localhost |
| port      | 3306      |
| dbname    | db_docker |
| user      | admin     |
| pass      | P@ss1234  |
| root_pass | P@ss1234  |

## Validar version docker-compose

```sh
docker-compose --version
```

## Acciones

### Levantar la imagen

```sh
docker-compose up -d
```

### Detener la imagen

```sh
docker-compose stop
```

### Borrar la imagen (y lo que conlleva)

```sh
docker-compose down
```

## Consultar archivo local

```sh
cd /usr/shared/ && ls && cat hello.txt | nl
```
