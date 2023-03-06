# docker template

## install:
- cоздать проэкт composer create-project laravel/laravel example-app 
    или указать версию laravel (composer create-project laravel/laravel:^9.0 example-app)
- скопировать фаилы в проэкт docker-template в проэкт ( уже можно запускать на default )
- можно настроить сборку под себя (поменять версию php, mysql, puth) если надо.
- в .env прописать пути к базе для подкулючения к mysql

## docker compands:
- start: docker-composse up -d
- stop: docker-compose down

