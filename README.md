# PHP Login and Registration Form
This is a simple PHP web application that allows users to register for an account and log in using their credentials. The application is built using PHP and MySQL and includes a security feature for hashing passwords.

# Features
User registration: users can create an account by providing a username and password <br>
User login: registered users can log in using their credentials <br>
Password hashing: user passwords are hashed for security purposes <br>
MySQL database: user data is stored in a MySQL database <br>
# Requirements
PHP 7.0 or higher <br>
MySQL 5.7 or higher <br>
# Installation
Clone this repository: git clone https://github.com/namanshah22/login-and-registration-form <br>
Create a new MySQL database <br>
Import the SQL file located in the database folder into your new database <br>
Edit the config.php file and update the database connection details <br>
Upload the entire application to your web server <br>
Visit the application in your web browser <br>
# Usage
Register for an account by clicking the "Register" link on the login page and providing a username and password <br>
Log in using your registered username and password <br>

# Security
User passwords are hashed using the PHP password_hash() function for added security <br>
SQL injection attacks are prevented using prepared statements <br>
# Credits
This project was created by Naman Shah.
