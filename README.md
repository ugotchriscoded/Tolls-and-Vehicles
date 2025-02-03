<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# 🚧 Vehicles and Tolls 🚗

## :bulb:Project description

I made a **program** to model a **toll system**. 

Toll station have a **name**, the **city** in which they are located, and a **numerical value** that represents the **total amount** of **toll collected**.

Vehicles arriving at a toll have a **license plate**. 

The **toll amount** charges depending on the **vehicle type**:

- 🚗: *$100*

- 🏍: *$50*

- 🚚: *$50 is charged for each axle.*

**Toll station** is required to calculate:

- *Toll amount for each vehicle that arrives.*
- *Total amount of pesos collected.*

**System** must print on the screen:

- *List of the vehicles that arrived at the toll.* 
- *Total accumulated.*

## Requirements:

- **Database** design.
- **API** to add the passage of a vehicle in one of the defined standards.
- Print for each toll, 1 all the vehicles that have passed with their price and the total **(BLADE)**.
- Print for each vehicle how much it has paid in pesetas in total adding all the pesetas through which it has passed.**(BLADE)**.
- **Minimum** coverage 70%.

## :eye_speech_bubble: Working app

(insert screenshoots)

## :file_folder: Jira Backlog

(insert screenshoots)

## :paperclip: Installation requirements
:black_circle: XAMPP

:black_circle: Composer

:black_circle: Node.js (Installing NPM)

:black_circle: Xdebug 

:black_circle: Postman

> [!NOTE] 
If you can't install XAPP, you can also use another local server that supports MySQL and PHP.

## :scroll: Installation

### Step 1: Creating database

Creating a database in **Admin** **SQL**.

(insert screenshoot)

### Step 2: Cloning repository

```php
https://github.com/ugotchriscoded/Tolls-and-Vehicles
 ```

 ### Step 3: Putting everything up to date

In the *.env* file **remove** the *#* in these lines, enter the **name** of your **database** and **replace** *Laravel* with *sql*.

<p align="center"><img width="287" alt="image" src="https://github.com/user-attachments/assets/bdfec806-cdcc-4a05-a6bf-43a59cc7658e"></p>

### Server

To **run the server** enter this command:

```php
npm run dev
```

(insert screenshoot)

> [!WARNING]
> **DON'T work** on that terminal again, but you should keep it working. **DON'T KILL IT.**

To see the **running serve** enter the command:

```php
php artisan serve
```
(insert screenshoot)


> [!NOTE]
> If you press Control and click the link it should take you to the main offers.


## 📝 Documentation (Endpoints)

## :white_check_mark: Tests

> [!IMPORTANT]
>  Testing the project so we can check if it works correctly using this command:

```php
./vendor/bin/phpunit tests
```
(insert screenshoot)

### Coverage

Use this command:

```php
php artisan test --coverage
```

(insert screenshoot)

## Authors
Developed by **Valeria Dobado Gonzalez**:
- **Github**: *https://github.com/ugotchriscoded/ugotchriscoded*
- **Linkendin**: *https://www.linkedin.com/in/valeria-dobado-gonzález-262060328/*

## Languages
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='php' src='https://img.shields.io/badge/php-100000?style=for-the-badge&logo=php&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='css3' src='https://img.shields.io/badge/css3-100000?style=for-the-badge&logo=css3&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='json' src='https://img.shields.io/badge/JSON-100000?style=for-the-badge&logo=json&logoColor=white&labelColor=000000&color=000000'/></a>

## Tools
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='github' src='https://img.shields.io/badge/github-100000?style=for-the-badge&logo=github&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='Laravel' src='https://img.shields.io/badge/Laravel-100000?style=for-the-badge&logo=Laravel&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='Git' src='https://img.shields.io/badge/git-100000?style=for-the-badge&logo=Git&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='MySql' src='https://img.shields.io/badge/my_sql-100000?style=for-the-badge&logo=MySql&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='xampp' src='https://img.shields.io/badge/xampp-100000?style=for-the-badge&logo=xampp&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='xampp' src='https://img.shields.io/badge/postman-100000?style=for-the-badge&logo=xampp&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='Jira' src='https://img.shields.io/badge/Jira-100000?style=for-the-badge&logo=Jira&logoColor=white&labelColor=black&color=black'/></a>

## Thanks for reading!

Thanks for your attention, have a nice day! <3
