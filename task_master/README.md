# Task Manager with PHP and MySQL

## Technologies Used
1. Core PHP Programming Language (Procedural Programming)
2. MySQL Database
3. HTML
4. CSS

## How to Download and Run on your PC?



### Installtion

1. Download as as Zip or Clone this project
2. Move this project to Root Directory
```
Local Disc C: -> xampp -> htdocs -> 'this project'
```
*Local Disk C is the location where xampp was installed*

3. Open XAMPP Control Panel and Start 'Apache' and 'MySQL'

4. Import Database

a. Open 'phpmyadmin' in your browser
b. Create a Database
c. Import the SQL file provided with this project

5. Make Changes to settings

Go to 'config' folder and Open 'constants.php' file. Then make changes on following constants
```php
<?php 
//Start Session
session_start();

//Create Constants to save Database Credentials
define('LOCALHOST', 'localhost');
define('DB_USERNAME', ''); // Database username 
define('DB_PASSWORD', ''); // Database Password 
define('DB_NAME', 'task_manager'); // Database Name 

define('SITEURL', 'http://localhost/task-manager/'); 
?>
```

6. Now, Open the project in your browser. It should run perfectly.

