# Arc Skeleton

Application skeleton for the [Arc framework](https://github.com/rgusseinov/arc-php-framework).

## Install

```bash
composer create-project rgusseinov/arc-skeleton my-app
cd my-app
cp .env.example .env
php arc serve
```

## Structure

- `app/` your application code (`App\` namespace)
- `bootstrap/` application and console bootstrap
- `config/` app, database, logging, routes, generators
- `migrations/` database migrations
- `public/` web root
- `storage/` logs

## Commands

Run `php arc` to list available commands.
