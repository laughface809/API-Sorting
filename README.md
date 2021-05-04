<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

<h1 align="center">Full Rest API</h1>

## Endpoints

- GET localhost/api/frontend
- GET localhost/api/backend
- GET localhost/api/backend?s=
- GET localhost/api/backend?s=&sort=

Remember To Run factory for fake data, and All data is limit or paginated by 6.

## Installation
1. Clone this project and cd
    ```bash
    ```
2. Install dependencies
    ```bash
    composer install
    ```
    And javascript dependencies
    ```bash
    yarn install && yarn dev

    #OR

    npm install && npm run dev
    ```

3. Set up Laravel configurations
    ```bash
    copy .env.example .env
    php artisan key:generate
    ```

4. Set your database in .env

5. Migrate database
    ```bash
    php artisan migrate
    ```

6. Serve the application
    ```bash
    php artisan serve
    ```

## Contributing
Feel free to contribute and make a pull request.
