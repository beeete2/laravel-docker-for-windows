Laravel on Docker for Windows
-------------------------------------

### build
```bash
docker-compose build
```

### run
```bash
docker-compose up -d
```

### Install the Laravel
You can enter the application container.
`docker-compose exec php56 bash`

```bash
cd /app
composer create-project --prefer-dist laravel/laravel . "5.4.*"
php artisan serve --host 0.0.0.0 --port 8080
```
