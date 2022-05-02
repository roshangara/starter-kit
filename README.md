# Codespace Starter Kit


## Quick Installation in local

```bash
cp .env.example .env
```
- then
```bash

docker network create app

docker compose pull

sudo chown -R 5050:5050 storage/pgadmin/

docker compose up -d mariadb postgres redis minio phpmyadmin pgadmin meilisearch mailhog selenium nginx

```

### Ports

```text
mariadb:3306
```
```text
postgres:5432
```
```text
redis:6379
```
```text
mailhog:1025
```


### Minio

- admin:
[https://minio.codespaces.ir/](https://minio.codespaces.ir/)
- api:
[https://storage.codespaces.ir/](https://storage.codespaces.ir/app)


### Phpmyadmin

- [https://phpmyadmin.codespaces.ir](https://phpmyadmin.codespaces.ir)

### PGAdmin

- [https://pgadmin.codespaces.ir/](https://pgadmin.codespaces.ir/)

### Meilisearch

- [https://meilisearch.codespaces.ir](https://meilisearch.codespaces.ir)

### Mailhog

- [https://mailhog.codespaces.ir/](https://mailhog.codespaces.ir/)


### Selenium

- [https://selenium.codespaces.ir](https://selenium.codespaces.ir)


# Tools

Generate password:
```bash
date +%s | sha256sum | base64 | head -c 32 ; echo
```