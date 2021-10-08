
## Features 
- Automatic cross sell / up sell / related product offerings
- Open Source
- Ecommerce Solution

## Requirements

	PHP = ^7.3|^8.0
    laravel-ui = ^3.2

## Install

Clone repo

```
git clone https://github.com/Zulkarnine43/Ecom-POS.git
```

Install Composer


[Download Composer](https://getcomposer.org/download/)


composer update/install 

```
composer install
```

Install Nodejs


[Download Node.js](https://nodejs.org/en/download/)


NPM dependencies
```
npm install
```

Using Laravel Mix 

```
npm run dev
```

## How to setting 

Go into .env file and change Database and Email credentials.

```
php artisan migrate
```

```
php artisan db:seed --class=UserSeeder
php artisan db:seed --class=UserRoleSeeder
php artisan db:seed --class=DatabaseSeeder
```
	
Generating a New Application Key
```
php artisan key:generate