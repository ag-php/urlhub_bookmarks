<h4>Warning: The Plur is still under development.</h4>

![screenshot](https://i.imgur.com/0hF2dpc.jpg)
<h1 align="center">A modern and robust URL shortener built with Laravel.</h1>

Plur is a open-source link shortening web application. It allows you to host your own URL shortener, and to brand your URLs. Plur is especially easy to use, and provides a modern, themable feel.

### Features
* Written in PHP and powered by the Laravel 5.7.
* Modern and simple interface.
* Made with :heart: &amp; :coffee:.

## Requirements
- [All requirements by Laravel](https://laravel.com/docs/installation#server-requirements) - PHP, OpenSSL, [Composer](https://getcomposer.org/) and such.
- MySQL or MariaDB.


## Quick Start
### Installation Instructions
1. Run `composer install`.

2. Rename `.env.example` file to `.env` or run `cp .env.example .env`.

   Update `.env` to your specific needs. Don't forget to set `DB_USERNAME` and `DB_PASSWORD` with the settings used behind.

3. Run `php artisan key:generate`.

4. Run `php artisan migrate --seed`.

5. Run `php artisan serve`.

   After installed, you can access http://localhost:8000 in your browser.

6. Login

   | Email           | Username | Password | Access       |
   |-----------------|----------|----------|--------------|
   | admin@plur.test | admin    | admin    | Admin Access |
   | user@plur.test  | user     | user     | User Access  |

### Compiling assets with Laravel Mix
#### Using NPM:
1. From the projects root folder run `npm install`
2. Run `npm run dev` or `npm run prod`
  * *You can watch assets with `npm run watch`*

#### Using Yarn:
1. From the projects root folder run `yarn install`
2. Run `yarn run dev` or `yarn run prod`
  * *You can watch assets with `yarn run watch`*


## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the repository.
2. Hack on a separate topic branch created from the latest `master`.
3. Commit and push the topic branch.
4. Make a pull request.
5. Welcome to the club :sunglasses: and thank you for helping out!


## License
Plur is an open-sourced software licensed under the [MIT license](https://github.com/realodix/plur/blob/master/LICENSE).
