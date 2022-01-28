Work in progress

-   Backend for: ....

## Setup / init for development

-   ddev start
-   ddev composer install
-   ddev launch
-   (TODO: artisan generate key?)
-   npm install
    (because of https://github.com/prettier/plugin-php#vscode, doesn't work with global install)

## Deployment

-

## How was this created?

1. DDEV laravel composer quickstart (https://ddev.readthedocs.io/en/stable/users/cli-usage/#laravel-composer-setup-example)
1. Tutorial: https://www.youtube.com/watch?v=3GpQPa8z9qc&list=PLe30vg_FG4ORwyiMX8qW5tn4jX_0EcpDt&index=2
1. ddev composer require nuwave/lighthouse
1. ddev artisan vendor:publish --tag=lighthouse-schema
1. For prettier php support `npm install --save-dev prettier @prettier/plugin-php`
