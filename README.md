# Fullstack-App
Just a repo for practice building a fullstack web application

Intalled packages:

Guide: https://www.youtube.com/watch?v=vrj9AohVhPA

Uses XAMPP Control pannel for servers
- Run Apache and MySQL 
- Click the 'Admin' button next to the MySQL server to access database web interface

MySQL Database:
Database: web_app

Table setup: 

create table names (
    id          INT         11
    name        VARCHAR     100
    date_added  DATETIME
    PRIMARY KEY (id)
)

Express - 
MySQL - SQL server interface
dotenv - Allows us to use a .env file that stores config info and important files
Nodemon - auto updates the server after you make changes to scripts so you dont have to restart it every time
Cors - Used for API calls from frontend to backend 