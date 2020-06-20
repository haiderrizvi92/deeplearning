<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Laravel wrapper of BigBlueButton Conference application

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

## Big Blue Button 

BigBlueButton is an open-source web conferencing system. It is based on GNU/Linux operating system and runs on Ubuntu 16.04. In addition to various web conferencing services, it has integrations for many of the major learning and content management systems.

## This is the Wrapper of Laravel + BigBlueButton 

I have designed this wrapper for the ease of use to create online conferencing application in laravel, currently I am using laravel 5.3 for this application but in future I will update the laravel version. 

## Settings and Configuration

You can define Big blue button secret key and server url in two ways. 
1. Define in .env file

 ```BBB_SECURITY_SALT =bbb_secret_key```  
 ```BBB_SERVER_BASE_URL=https://example.com/bigbluebutton/``` 
 
 2. Define in config/bigbluebutton.php
 
```
 'BBB_SECURITY_SALT' => 'bbb_secret_key',
 'BBB_SERVER_BASE_URL' => 'https://example.com/bigbluebutton/',
```

## Via Laravel Facade
You can also manage meetings using the facade
```php
Meeting::all(); //get a list of all meetings
```

## Contact Developer

```Aliraza170@gmail.com```

