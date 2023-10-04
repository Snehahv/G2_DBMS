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
```sql
 create table student_table(Roll_no numeric(10) , Name varchar(20) , Age numeric(3), Address varchar(20) , Phone_no numeric(10));
```

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119104131/6903b635-564e-40c1-a2cc-465d4ffc4904)

![image](https://github.com/dineshgl/G2_DBMS/assets/119104131/1cf1fe85-bd9d-4b98-92d1-84b60cbe9184)



### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```sql
alter table student_table add Email varchar(100);
```

### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119104131/3a1e9e62-fd8d-4f9c-8275-454529f9b710)



### 3) Drop the student table
 
### SQL QUERY: 
```sql
Drop table student_table;
```


### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119104131/ea48865a-1e67-4859-9341-5589f2a16d11)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```sql
Truncate table student_table1;
```


### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119104131/42194a61-38ae-4a8b-9870-348300115a12)




### 5) Rename the student table to mystudent

### SQL QUERY: 
```sql
alter table student_table1 rename to mystudent;


### OUTPUT:
![image](https://github.com/dineshgl/G2_DBMS/assets/119104131/fecc6479-9990-4b9e-a1d7-cc72f49c8203)

