# Academy Next Top Model Website (v1)

Website for Academy Next Top Model, a modeling academy in Indonesia, built with **Laravel 12** and **MySQL**.
This is the first version, made as an academic project at Gunadarma University (May - Sep 2025).

> The latest version, including the NLP chatbot and admin dashboard, is available at
> [Nazwadna/academynexttopmodel](https://github.com/Nazwadna/academynexttopmodel).

## Features

- Register and login with WhatsApp OTP verification or Google sign-in
- "Join Academy" online registration form
- Model list and portfolio pages
- Admin page to add and edit model data

## Tech Stack

Laravel 12, PHP 8.2, MySQL, Blade, Tailwind CSS, Vite

## Run Locally

```bash
composer install
npm install
cp .env.example .env
php artisan key:generate
```

1. Create a MySQL database named `academyntm` and import `academyntm.sql`
   (table structure only, no user data).
2. Set the database name, user, and password in `.env`.
3. Run `npm run dev` and `php artisan serve`, then open http://127.0.0.1:8000
