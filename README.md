# SQL-Injection-DVWA
![](sQL-.png)

SQL injection is a code injection technique that might destroy your database. SQL injection is one of the most common web hacking techniques. SQL injection is the placement of malicious code in SQL statements, via web page input.

### Basic SQL
SQL is a standard language for storing, manipulating and retrieving data in databases.

### Start mysql service and login.
![](start%20mysql%20service.png)
### Create database name security.
Syntax - create database Database_name;<br>

Then use show tables; command to check tables exist in database.<br>
![](show%20tables.png)

### Now create table user and add column to it.
Syntax - Create table table_name(Column_name1 data_type, Column_name2 datatype, ....);
![](create%20table%20user.png)

### Insert values in table.
Syntax - Insert into table_name(Column_name1, Column_name2, ....) values (Value1, Value2, ....);
![](insert%20values%20in%20table.png)

### To select all data in table user
command - Select * from user;
![](select%20date%20from%20table%20user.png)

### To select database. use command - select database();
![](select%20database.png)

### To see all username present in table user.
command - select username from user;
![](see%20usernames%20present.png)

### Login query - Select password from user where username = 'root';
![](login%20query.png)


# To perform sql injection of severity low, medium and high refer to the documentation provided.
### (To be used for education purpose only !!)

