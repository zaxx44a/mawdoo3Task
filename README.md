## Ovreview
### Laravel Custom Package For Google Custom Search

## Requirement

- Laravel 5.7 (see [laravel Documentation](https://laravel.com/docs/5.7#server-requirements)) .
- composer ([install Inc](https://getcomposer.org/doc/00-intro.md)).
- mysql server .
##### meet that requirement then just complete this :

## installation 
##### edit .env file to your DB credentials :
       fix database name,user&pass in .env file  
##### install package via composer in your laravel directory :
       composer require mawdoo3/laravel-task
##### then the install command will be :
       php artisan task:install
##### run internal php server :
       php artisan serve
##### That's it !! :
       http://127.0.0.1:8000/search

## Configration
##### to change cx and api key :
add sp_mawdoo3_laravel_cx and sp_mawdoo3_laravel_key to .env file or change default value in config/customSearch.php
## License
This is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
