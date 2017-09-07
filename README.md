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

You need a valid certificate for multiples services (see config/nginx/conf.d/) and copy them on /config/ssl/

## First launch

```bash
$ docker-compose up
```
then test services deployed:
- https://elasticsearch.domain.com => Elasticsearch
- https://adminer.domain.com => phpmyadmin

Create a index example and go to https://elasticsearch.domain.com/_plugin/head
$ curl -XPOST https://elasticsearch.domain.com/test/hello -d '{"title":"Hello world"}'
