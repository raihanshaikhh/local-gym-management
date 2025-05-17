# 🏋️ Gym Membership Website

This is a simple Gym Membership Website that allows users to log in and store their membership data (email, joining date/time, and membership period). The site is powered by PHP and MySQL, and it runs locally on **XAMPP** server.


All files and assets are located inside the `login` folder.

## 🛠️ Requirements

- XAMPP (PHP & MySQL server)
- Web browser (e.g., Chrome, Firefox)

## 🧑‍💻 How to Run

### 1. 🔥 Start Apache and MySQL
Open **XAMPP Control Panel** and start:
- Apache
- MySQL

### 2. 📂 Place Project Folder

Copy your `login` folder to the XAMPP `htdocs` directory:


### 3. 🛢️ Set Up the Database

1. Open your browser and go to: http://localhost/phpmyadmin

2. Create a new database named: membership
3. 
3. Inside the `membership` database, create a table. You can use the following SQL query:

4. ⚙️ Configure Database Connection
5. 
Open the db.php file (or equivalent) in the login folder and ensure your MySQL connection looks like this:
<?php
$host = "localhost";
$user = "root";
$password = "";
$database = "membership";

$conn = new mysqli($host, $user, $password, $database);

if ($conn->connect_error) {
    die("Connection failed: " . $conn->connect_error);
}
?>
5. 🧪 Access the Website
Now open your browser and go to: http://localhost/login.php

Your Gym Membership Website should now be up and running!

📬 Contact
For any issues or suggestions, feel free to reach out.




