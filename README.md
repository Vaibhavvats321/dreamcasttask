Hello,
To configure this git repo here are the few steps to follow after cloning.

1) composer install & composer update
2) cp .env.example .env
3) Database name = dreamcasttask
4) php artisan key:generate
5) php artisan storage:link
6) php artisan migrate
7) php artisan serve
