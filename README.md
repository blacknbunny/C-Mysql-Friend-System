# C-Mysql-Friend-System
## Friend system with C

[![demo](https://asciinema.org/a/kxXh3hXJkZqoAPxLTAh7gAlUd.png)](https://asciinema.org/a/kxXh3hXJkZqoAPxLTAh7gAlUd?autoplay=1)

## System : 
Unix, Linux


## Compile parameters :
```gcc main.c -I/usr/include/mysql -L/usr/lib -lmysqlclient -lpthread -lz -lm -ldl -lssl -lcrypto ```


## Database :
MySQL


## Change The Defination variables

#### #define host "localhost"
#### #define user "root"
#### #define pass ""
#### #define databasename "user"


# 1. Table Command

##### CREATE TABLE added_friend( fromname VARCHAR(20), name VARCHAR(20) );

## 2. Table Command

##### CREATE TABLE infriend( friend VARCHAR(20), friend2 VARCHAR(20) );

### 3. Table Command

##### CREATE TABLE users( username VARCHAR(30), password VARCHAR(30), email VARCHAR(30) );
