web: php -r "file_exists('.env') || copy('.env.example', '.env');"
web: php artisan key:generate --verbose --ansi
web: vendor/bin/heroku-php-apache2 public/
