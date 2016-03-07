# Php 7 FPM Container for Laravel 

Installs these extensions and their dependencies.

 * json
 * mbstring
 * tokenizer
 * gd
 * curl
 * dom
 * bz2
 * mysqli
 * pcntl
 * pdo
 * pdo_mysql
 * phar
 * posix
 * simplexml
 * soap
 * tidy
 * zip
 * bcmath
 * calendar
 * ctype
 * exif
 * pcntl
 * pdo_sqlite

## Docker Compose Config

docker-compose.yml

```
...
php:
    image: kahunacoder/docker-laravel-php
    expose:
        - 9000
    links:
        - mysql
    volumes_from:
        - app
...
```
