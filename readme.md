# laravel-roles-example
An example of [jeremykenedy/laravel-roles](https://github.com/jeremykenedy/laravel-roles-example), a Laravel 5.4+ roles package.

## Setup
1. `sudo git clone https://github.com/jeremykenedy/laravel-roles-example.git laravel-roles-example`
2. `sudo composer update`
3. `sudo cp .env.example .env`
	* Configure `.env` file
4. `sudo php artisan key:generate`
5. `sudo php artisan migrate`
6. `sudo php artisan db:seed`

## Seeds
#### Users Seeded
|Property|Value|
|----|----|
|Username| Admin|
|Email| jeremykenedy@gmail.com|
|Password| password|
|Role| Admin|

|Property|Value|
|----|----|
|Username| User|
|Email| jeremy@jeremykenedy.com|
|Password| password|
|Role| User|

#### Roles Seeded
|Property|Value|
|----|----|
|Name| Admin|
|Slug| admin|
|Description| Admin Role|
|Level| 5|

|Property|Value|
|----|----|
|Name| User|
|Slug| user|
|Description| User Role|
|Level| 1|

|Property|Value|
|----|----|
|Name| Unverified|
|Slug| unverified|
|Description| Unverified Role|
|Level| 0|

#### Permissions Seeded:
|Property|Value|
|----|----|
|name|Can View Users|
|slug|view.users|
|description|Can view users|
|model|Permission|

|Property|Value|
|----|----|
|name|Can Create Users|
|slug|create.users|
|description|Can create new users|
|model|Permission|

|Property|Value|
|----|----|
|name|Can Edit Users|
|slug|edit.users|
|description|Can edit users|
|model|Permission|

|Property|Value|
|----|----|
|name|Can Delete Users|
|slug|delete.users|
|description|Can delete users|
|model|Permission|

---

<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb combination of simplicity, elegance, and innovation give you tools you need to build any application with which you are tasked.

## Learning Laravel

Laravel has the most extensive and thorough documentation and video tutorial library of any modern web application framework. The [Laravel documentation](https://laravel.com/docs) is thorough, complete, and makes it a breeze to get started learning the framework.

If you're not in the mood to read, [Laracasts](https://laracasts.com) contains over 900 video tutorials on a range of topics including Laravel, modern PHP, unit testing, JavaScript, and more. Boost the skill level of yourself and your entire team by digging into our comprehensive video library.

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](http://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell at taylor@laravel.com. All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
