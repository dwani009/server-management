This is server inventory management project built in laravel and free template: Admin Lte with MySql for database management.

## Requirements:
Laravel version: 6.0.1
PHP version: > 7

## What's inside
    • Adminpanel with default one admin user (admin@admin.com/password) 
    • Users/Roles/permissions management function 
    • CRUD for server management - name/description/price
    • Everything that is needed for CRUDs: model+migration+controller+requests+views

## How to use
    • Create new laravel project using command 'laravel new server-management' 
    • Create your database (in my case database name is 'serverhosting')
    • Edit .env file and modify database credentials there
    • Run **php artisan migrate --seed** (it has some seeded data for testing) or upload db directly with servermgmt.sql file which exixts in the root directory of the project
    • Run command **php artisan serve** and copy url once the server is started or run localhost on the browser
    • login using below credentials:
        email: admin@admin.command
        password: password
