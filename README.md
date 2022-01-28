Work in progress / Demo app for learning purposes

-   Backend for: ....

https://www.youtube.com/watch?v=x__yKzt0Pj4&list=PLe30vg_FG4ORwyiMX8qW5tn4jX_0EcpDt&index=3

## Setup / init for development

-   ddev start
-   ddev composer install
-   ddev artisan migrate
-   ddev launch
-   (TODO: artisan generate key?)
-   npm install
    (because of https://github.com/prettier/plugin-php#vscode, doesn't work with global install)

-   Endpoint: https://greenrunners-laravel-lighthouse-backend.ddev.site/graphql
-   Playground: https://greenrunners-laravel-lighthouse-backend.ddev.site/graphql-playground

## Deployment

-

## Technical docs

### How was this created?

1. DDEV laravel composer quickstart (https://ddev.readthedocs.io/en/stable/users/cli-usage/#laravel-composer-setup-example)
1. Tutorial: https://www.youtube.com/watch?v=3GpQPa8z9qc&list=PLe30vg_FG4ORwyiMX8qW5tn4jX_0EcpDt&index=2
1. ddev composer require nuwave/lighthouse
1. ddev artisan vendor:publish --tag=lighthouse-schema
1. For prettier php support `npm install --save-dev prettier @prettier/plugin-php`
1. Endpoint is now available: https://greenrunners-laravel-lighthouse-backend.ddev.site/graphql
1. composer require mll-lab/laravel-graphql-playground
1. Now playground is available: https://greenrunners-laravel-lighthouse-backend.ddev.site/graphql-playground
1. ddev artisan migrate => creates user tables
1. Add fake user:
   ddev artisan tinker
   User::factory()->create()
   (leave with "exit;")
1.
