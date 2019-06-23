# Symfony Microservices Application
Example of Microservices Application development using PHP

## Setup Guide
1. Make sure you are using php 7.1+, composer, and MySQL 
2. git clone git@github.com:Khachornchit/PHP-Symfony-4-Microservices.git
3. cd SymfonyMicroservices
4. composer install
5. Update mysql connection in .env file at DATABASE_URL
    * **Example**
    * DATABASE_URL=mysql://root:1234@127.0.0.1:3306/microservices
6. Run follow command 6.1-6.2 to create database and table in MySQL
    * 6.1 php bin/console doctrine:database:create
    * 6.2 php bin/console doctrine:migrations:migrate

## Command List
### Hello
    * php bin/console pluto:hello
    
### CREATE User
    * php bin/console pluto:user:create
    
### READ User
    * php bin/console pluto:user:read

### UPDATE User
    * php bin/console pluto:user:update

### DELETE User
    * php bin/console pluto:user:delete
