# Laravel Docker
### Create vendor File
```
docker-compose exec app composer update --no-scripts
```
### Run application

```
docker-compose up -d --build
```

### Close application

```
docker-compose kill
```

### Key generate

```
docker-compose exec app php artisan key:generate
```

### Composer install

```
docker exec app composer install
```

### Migrate

```
docker exec app php artisan migrate
```
