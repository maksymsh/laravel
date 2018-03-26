## Install project

- Clone project
```bash
git clone https://github.com/maksymsh/laravel.git
```
- Copy .env.example to .env and configure DB
- Install dependencies

```bash
composer install
```

- Generate key
```bash
php artisan key:generate
```

- Run migrations
```bash
php artisan migrate
```

- Run seeds
```bash
php artisan db:seed
```
