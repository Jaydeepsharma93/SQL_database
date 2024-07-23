# SQL_database

##  create a DBMS for employees.

```sql 
CREATE TABLE "Employess" (
	"id"	INTEGER,
	"name"	TEXT NOT NULL,
	"role"	TEXT NOT NULL,
	"salary"	INTEGER NOT NULL,
	"age"	INTEGER NOT NULL,
	"address"	TEXT NOT NULL,
	"phone"	INTEGER NOT NULL,
	PRIMARY KEY("id" AUTOINCREMENT)
);
```

## Add a new employee with all details

```sql
INSERT INTO Employess (name,role,salary,age,address,phone)
VALUES("Hariom","Salesman",5000,18,"141,suncity",9079772485)
```
