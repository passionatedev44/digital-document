![image](public/docs/images/DigiDocu_Mokup.jpg)
# DigiDocu
DigiDocu is a free, open source document management system built with laravel. Which provide easy way to 
manage documents with features like permissions, resize & compress images, combine multiple images into single pdf, 
zip all files etc..

## Installation
1. Download latest release from [here](#) or clone repository.
2. Run `composer install`.
3. Copy & setup `.env` file.
4. Create database & Change `DB_DATABASE` in `.env`.
5. Migrate the Database `php artisan migrate`.
6. Run `php artisan key:generate`
7. Run `php artisan db:seed` (This will generate super-admin & basic settings [required]).
8. Visit url in browser

##### Default Login Credential for super admin
| Username | Password |
|----------|----------|
| super    | 123456   |

## Documentation
1. [User Documentation](#)
2. [Developer Documentation](#)


## Troubleshooting
 - Run `php artisan cache:forget spatie.permission.cache` in case you have problem
 with permissions.
