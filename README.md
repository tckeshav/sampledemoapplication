
its a simple demo application program which is used for Register and Login.


to execute this application need to create following Database and table in DB.

CREATE DATABASE myusers; 
use myusers;
 CREATE TABLE `myusers`.`users` 
                 ( 
                              `username`  VARCHAR(45) NOT NULL, 
                              `password`  VARCHAR(45) NULL, 
                              `firstname` VARCHAR(45) NOT NULL, 
                              `lastname`  VARCHAR(45) NULL, 
                              `email`     VARCHAR(45) NULL, 
                              `address`   VARCHAR(45) NULL, 
                              `phone`     INT NULL, 
                              PRIMARY KEY (`username`) 
                 );
