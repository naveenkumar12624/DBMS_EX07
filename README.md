# Exp 7 Aggregate function in SQL.
## AIM:
To write a sql query to perform Aggregate function in SQL.
## PROCEDURE:
### STEP 1:
create database AGGREGATE_FUNCTION.
### STEP 2:
create table DETAILS with ID and value.
### STEP 3:
Insert Value to the table DETAILS.
### STEP 4:
Perform Aggregate functions like SUM(),COUNT(),AVG().
## PROGRAM:
```sql
CREATE DATABASE AGGREGATE_FUNCTION;
USE AGGREGATE_FUNCTION;
CREATE TABLE DETAILS (
  ID INT PRIMARY KEY,
  Value INT
);
INSERT INTO DETAILS (ID, Value) VALUES
(1, 10),
(2, 20),
(3, 30),
(4, 40),
(5, 50);
SELECT * FROM DETAILS;
SELECT SUM(Value) FROM DETAILS;
SELECT COUNT(*) FROM DETAILS;
SELECT AVG(Value) FROM DETAILS;
```
## OUTPUT:
![image](https://github.com/Karthikeyan21001828/DBMS_EX07/assets/93427303/45884ba1-9f50-4419-864d-84d1652fe84a)

![image](https://github.com/Karthikeyan21001828/DBMS_EX07/assets/93427303/870e4253-9628-40bd-bfee-abf8bfd2355a)

![image](https://github.com/Karthikeyan21001828/DBMS_EX07/assets/93427303/7cf5ef0a-17f4-4fe3-8ec7-537b706cfe8d)

![image](https://github.com/Karthikeyan21001828/DBMS_EX07/assets/93427303/a9f20597-edab-4a01-962e-279ce5f290d0)


## RESULT:
A sql query to perform Aggregate function in SQL has been executed.
