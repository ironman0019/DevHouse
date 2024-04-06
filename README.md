# Dev House project

A full website for posting programming jobs with login & register system and CRUD functionality and more!

## Installation
1. Clone the project
2. Navigate to the project's root directory using terminal
3. Create `.env` file - `cp .env.example .env`
4. Execute `composer install`
5. Set application key - `php artisan key:generate --ansi`
6. Execute migrations and seed data - `php artisan migrate --seed`
7. Start Artisan server - `php artisan serve`