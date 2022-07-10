# Laravel Docker

# Install

**1. Clone Project**

```
  $ https://github.com/fsarikaya96/laravel-docker.git
```

**2. Install**

```
  $ docker-compose up -d
  $ docker exec app composer install
  $ docker exec app php artisan key:generate
  $ docker exec app php artisan migrate
```

**3. Url & phpMyAdmin**

```
 http://localhost:8080
 http://localhost:8081
```
