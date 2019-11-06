https://gist.github.com/15Dkatz/321e83c4bdd7b78c36884ce92db26d38
The instructions for install postgres and the path variable set steps are at the link above

The link for postgreSQL
https://www.enterprisedb.com/downloads/postgres-postgresql-downloads

install and set username and password
REMEMBER TO INSTALL TO C DRIVE NOT PROGRAM FILES
add system environment variables based on location of psql.exe
typically in C:/PostgreSQL/bin
also add the lib folder
C:/PostgreSQL/lib

go to bash
run the following command to access the local sqlserver
psql -U postgres postgres 
type in password

run sql commands like
1) create database b_buddy_users;
REMEMBER THE SEMICOLON

2) \q to exit the main database
3) psql -U postgres [name of new database]

AND ONCE YOU'RE IN THE DATABASE
4) CREATE TABLE b_buddy_users(name character varying(50));
^^^ this makes a table within the database you are accessing

to access your postgres server use pgAdmin and it should automatically connect to localhost



