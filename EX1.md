# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:

### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 


### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119104131/17ca32e3-9733-4517-8ef8-f5512e982feb)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119104131/de5643f8-3335-4104-8bbd-9452323e5828)



### 3) Drop the student table
 
### SQL QUERY: 


### OUTPUT:


### 4) Delete the student table using truncate keyword

### SQL QUERY: 


### OUTPUT:



### 5) Rename the student table to mystudent

### SQL QUERY: 


### OUTPUT:
