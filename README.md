This is a laravel-react raw file without authentication(breeze) just a starter kit
composer install 

npm install
npm run dev
cp .env.example .env
php artisan key:generate
touch database/database.sqlite
php artisan migrate
php artisan db:seed
php artisan serve

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
