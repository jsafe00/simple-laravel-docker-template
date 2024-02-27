## Simple Laravel Docker Template

#### New Project

```
cd src/
```

```
composer create-project laravel/laravel .
```

#### Existing Project

Replace with existing source code of your existing Laravel instance

```
cd src/
```

In the docker folder, execute:

```
docker-compose up
```

DB Migration

MYSQL_ROOT_PASSWORD: root

In the src folder, execute:

```
php artisan migrate
```

Accessing laravel project in the browser:

```
localhost:8000
```