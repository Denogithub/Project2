## Project 2 LEMP Implementation

`sudo apt update``sudo apt install nginx`
`sudo systemctl status nginx`
![nginx status](./images/nginx-status.PNG)

'curl -s http://54.144.127.1/latest/meta-data/public-ipv4'
![nginx web status](./images/nginx-web-status.PNG)

'sudo apt install mysql-server`' sudo mysql-u root -p'
![mysql status](./images/Mysql-p2.PNG)

'http://`54.144.127.1`/info.php`
![php status](./images/php-status.PNG)

'CREATE DATABASE `project2_db`;`
![DB status](./images/Dennis_DB-access.PNG)

'INSERT INTO project2_db.todo_list`'SELECT * FROM example_database.todo_list;'
![php status](./images/Dennis_db_test.PNG)

'http://`54.144.127.1`/todo_list.php`
![php status](./images/PHP_Webcontent_script.PNG)