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

## Add a new employee with all details:

```sql
INSERT INTO Employess (name,role,salary,age,address,phone)
VALUES("Hariom","Salesman",5000,18,"141,suncity",9079772485);
```
## Add multiple employees with selective data:

```sql
INSERT INTO Employess (name,role,salary,age,address,phone)
VALUES("Harish","Salesman",2000,18,"141,suncity",9079772485),
      ("Hitesh","Salesman",10000,20,"141,suncity",9079772485),
      ("Ram","Salesman",8000,17,"141,suncity",9079772485),
      ("Ankit","Salesman",3000,19,"141,suncity",9079772485);
```
## Retrieve all employee information:
```sql

SELECT * FROM Employess;
```
## Get specific columns for all employees (e.g., name, salary):
```sql

SELECT name,salary FROM Employess;
```

## Find employees with a specific role (e.g., Manager):
```sql

SELECT role FROM Employess;
```

## Search for employees with names containing "An" (case-insensitive):
```sql
```
```sql
```
