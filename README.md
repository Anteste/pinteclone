# PinteClone

PinteClone can be used:
 - to find the best picture that you need.
 
Programming languages & Frameworks used:
  - PHP
  - Javascript
  - Twig
  - Css (Bootstrap)
  
PHP Framework used: Symfony 5.2.6
Database: MySQL

INSTALLATION:
- Clone the project
```sh
$ git clone https://github.com/Anteste/symbnb.git
```

- Install dependencies
```sh
$ composer install 
```

- Configure your database in the .env file
```sh
DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name?serverVersion=5.7.31
```

- Start migrations
```sh
$ php bin/console doctrine:migrations:migrate
```

- Start the server 
```sh
$ symfony serve
```
