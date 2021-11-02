### Laravel implementation of RealWorld app

This Laravel app is part of the [RealWorld](https://github.com/gothinkster/realworld) project and implementation of the [Laravel best practices](https://github.com/alexeymezenin/laravel-best-practices).

See how the exact same Medium.com clone (called [Conduit](https://demo.realworld.io)) is built using different [frontends](https://codebase.show/projects/realworld?category=frontend) and [backends](https://codebase.show/projects/realworld?category=backend). Yes, you can mix and match them, because **they all adhere to the same [API spec](https://gothinkster.github.io/realworld/docs/specs/backend-specs/introduction)**

### How to run the API

Clone the repo, enter the project folder and run these commands to install the app

```
 composer install
 cp .env.example .env
```

Run the web server

```
php artisan serve
```

That's it. Now you can use the api, i.e.

```
http://127.0.0.1:8000/api/articles
```
