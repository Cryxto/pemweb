# Struktur Folder Project Pemrograman Web CR001

# Cara set project

## Build menggunakan docker-compose

`docker-compose up -d --build`

## Masuk ke shell atau bash container

`docker exec -it pemweb bash`

## Install laravel 9 menggunakan shell atau bash container yg berisi php

`composer create-project laravel/laravel:^9.0 .`

## Jika error laravel log gunakan ini didalam container shell atau bash

`chown -R www-data:www-data /var/www`
