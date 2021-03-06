## Introduction

This is a mini medical practice management system. 

### Core Features
This application has views to.

- ```CREATE```, ```READ```, ```UPDATE``` and ```DELETE``` Practices

- ```CREATE```, ```READ```, ```UPDATE``` and ```DELETE``` Employees

- ```CREATE```, ```READ```, ```UPDATE``` and ```DELETE``` Fields of Practices

### How to access the app online


Live URL can be accessed [here](https://laravel-transfer-api.herokuapp.com)

### How to run the app locally
- Clone the repo.
- Run ```composer install``` (visit [the official website](https://getcomposer.org/) to get started).
- Create a ```.env``` file in the root directory (check ```.env.example``` for required keys and supply appropriate values).
- Generate your application key with ```php artisan key:generate```
- Run your migration with ```php artisan migrate``` (you should have your credentials set in your .env before doing this).
- Run your seeder with ```php artisan db:seed``` (this will create a sample admin user for you with the credentials below).
- **username: email@mailer.com**
- **password: pass123word**
- ```php artisan serve``` should spin up the application on port 8000 (you should see something like this: (Starting Laravel development server: http://127.0.0.1:8000)


### You should be up and running by now!