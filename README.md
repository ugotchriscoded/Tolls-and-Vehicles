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
