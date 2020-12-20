# itp-foodcal
 ### Requirement System 
    - PHP 7.4.13 + 
        - PHPLibrary (PDO , PDO_MYSQL)
    - MariaDB 10.4.16 or MySQL 5+

#### How to get started
    1. import database file to database systems and set name dabase "food_db"
    2. edit config database on the file /config/db-config.inc.php
    3. changes variable 
        - $server -> edit to hostname database system ($server = "localhost")
        - $username -> edit to username database system ($username = "root")
        - $password -> edit to password database system ($password = "") 
        ** (if using xampp you can set empty password and $username = "root")

##### Description of the work
    - using PHP PDO (+ Prepared Statements)
    - using multiselect (bootstrap-select)
    - using ajax (file path : /js/home.js) send dataform and get response dataType Json 