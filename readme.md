[![Build Status](https://travis-ci.com/specialtactics/laravel-api-boilerplate.svg?branch=master)](https://travis-ci.com/specialtactics/l5-api)
[![StyleCI](https://github.styleci.io/repos/131504554/shield?branch=master)](https://github.styleci.io/repos/131504554)

<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

## About Laravel API Boilerplate
This is a boilerplate for writing RESTful API projects using Laravel. The aim of this boilerplate is to provide developers with scaffolding and common functionality which will make writing APIs exceedingly quick, efficient and convenient.

It is intended for this repository to be used when starting a new API project. Therefore, instead of cloning the laravel repository, you should clone this one.

The principles of this boilerplate are to;

 - Save developers considerable effort by using reasonable conventions
 - Allow for everything the boilerplate provides to be easily extended and entirely customised to suit developer needs, through normal PHP inheritance
   - As well as allow developers to easily use the boilerplate functionality and mix it in with their own implementation
 - Follow REST standards very closely
 - Use existing Laravel features and existing Laravel add-on packages where possible
 - Add many convenient features useful for writing APIs
 - Maintain a high level of performance

## Documentation
For setup, usage guidance, and all other docs - please consult the [Project Wiki](https://github.com/specialtactics/l5-api-boilerplate/wiki).

## Contributing

If you would like to contribute to this project, please feel free to submit a pull request. If you plan to do any major work - it may be worthwhile messaging the author beforehand to explain your plans and get them approved.

Please keep in mind, this package is only the template portion of the boilerplate, the main portion is [l5-api](https://github.com/specialtactics/l5-api). 
Before adding any new functionality, you should consider whether it's possible at all to keep it out of this project and rather put it into l5-api, as that is preferred.

## Check out the documentation of supporting projects

Every great project stands on the shoulders of giants. Check out the documentation of these key supporting packages to learn more;

 - [Laravel](https://laravel.com/docs/)
 - [Dingo API](https://github.com/dingo/api/wiki)
 - [Tymon JWT Auth](https://github.com/tymondesigns/jwt-auth)
 - [League Fractal](https://fractal.thephpleague.com/)
 - [Laravel UUID](https://github.com/webpatser/laravel-uuid/tree/2.1.1)

## Recommended Packages

I have tried to include only the packages thought absolutely necessary, so here is a list of packages I recommend checking out:

#### General 
 - [PHP CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer)
 - [PHP-VCR](https://github.com/php-vcr/php-vcr)

#### For Debugging 
 - [Bugsnag for Laravel](https://github.com/bugsnag/bugsnag-laravel)
 - [Sentry](https://github.com/getsentry/sentry-laravel)

## License
 
This boilerplate, much like the Laravel framework is open-source software licensed under the [MIT license](https://opensource.org/licenses/MIT).

Laravel Template API
About
This is a RESTful API template with Laravel. A good number of elements are configured and put in place to facilitate development instead of starting from scratch, Using JWT Authenticator

Installation
After cloning the project, you must use the package manager Composer to install all dependencies.

Cloning project
git clone https://github.com/bolenge/laravel-template-api.git
Installation dependencies
composer install
Initialization
Rename file .env.example to .env
Update database and other informations
Generate app key (If you don't have APP_KEY value in .env)
php artisan key:generate
JWT token
php artisan jwt:secret
Run Migrations
php artisan migrate
Generate Storage link
php artisan storage:link
Initialize seeds
php artisan db:seed
Run tests
php artisan test
Start server
php artisan serve
Api Documentation
e.g : localhost:8000/api/docs
App Home Page
e.g : localhost:8000
Contributing
@bolenge
License
MIT license.

