<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


## Laravel Trait example

  Create the database name "traits" <br />
  Run "php artisan migrate"<br />
  Start the server - php artisan serve <br />
  open the following url - http://localhost:8000/students

  ## What is useful about this?
  This helps you understand when is a good time to use traits. In the example <br />
  The controller "StudentController" has a class called "StudentContoller" and inside <br />
  the controller there isn't a method as usual, but instead there is a "USE" reference <br />
  to the student trait which is in the directory - App\HTTP\Traits and it's called <br />
  "StudentTrait.php". <br />
  That file is querying the database and passing all the students to the welcome blade file and displaying them.



