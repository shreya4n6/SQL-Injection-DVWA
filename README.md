# :fire: SQL-Injection-DVWA
![](sQL-.png)

:fire: SQL injection is a code injection technique that might destroy your database. SQL injection is one of the most common web hacking techniques. SQL injection is the placement of malicious code in SQL statements, via web page input.

### :fire: Basic SQL
SQL is a standard language for storing, manipulating and retrieving data in databases.

### :fire: Start mysql service and login.
![](start%20mysql%20service.png)
### :fire: Create database name security.
Syntax - create database Database_name;<br>

Then use show tables; command to check tables exist in database.<br>
![](show%20tables.png)

### :fire: Now create table user and add column to it.
Syntax - Create table table_name(Column_name1 data_type, Column_name2 datatype, ....);
![](create%20table%20user.png)

### :fire: Insert values in table.
Syntax - Insert into table_name(Column_name1, Column_name2, ....) values (Value1, Value2, ....);
![](insert%20values%20in%20table.png)

### :fire: To select all data in table user
command - Select * from user;<br>
![](select%20date%20from%20table%20user.png)<br>

### :fire: To select database. use command - select database();<br>
![](select%20database.png)<br>

### :fire: To see all username present in table user.
command - select username from user;<br>
![](see%20usernames%20present.png)<br>

### :fire: Login query - Select password from user where username = 'root';
![](login%20query.png)


# :fire: To perform sql injection of severity low, medium and high refer to the documentation provided. :point_up::point_up::point_up:
### (To be used for education purpose only !!)

