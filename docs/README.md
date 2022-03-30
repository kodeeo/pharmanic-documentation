# Backend Installation :

```bash
git@github.com:kodeeo/pharmanic-backend.git
cp .env.example .env
composer update
php artisan key:generate
create database
In .env file add database name and user name(root)
php artisan migrate
php artisan db:seed
php artisan tinker
App\Models\User::factory()->create()
php artisan serve
```

For import package and product: In terminal `php artisan import:ndc`
