My-compose over Nginx
==============

## Services deployed:

- Redis
- Elasticsearch
- Mariadb
- Phpmyadmin
- Nginx

## Quick start

- docker
- docker-compose

## Configure

To run, you need a valid certificate for multiples services:
- elasticsearch
- phpmyadmin

## First launch

```bash
$ docker-compose up
```
then open multiple services:
- https://elasticsearch.domain.com => Elasticsearch
- https://adminer.domain.com => phpmyadmin
