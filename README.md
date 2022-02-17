# Trying out Laravel 9 features

Repo was created to support the article at https://medium.com/@mazraara/whats-new-with-laravel-9-b2f5e84c9094

To run:

- copy .env.example to .env
- update database credentials in the env
- composer i
- php artisan key:generate
- php artisan migrate:fresh --seed
- update algolia api keys in the env (optional)
