## INIT

- <code>cp .env.example .env</code>
- ubah data .env dibawah sesuai dengan pengaturan database anda:
    <pre>
        DB_DATABASE=guesthouse
        DB_USERNAME=root
        DB_PASSWORD=
    </pre>
- ubah APP_URL di file env sesuai pengaturan anda.
- composer install
- php artisan key:generate
- php artisan migrate
- php artisan admin:install
