# DBMS-mini-project
INTRODUCTION
In this world of growing technologies everything is now computerised. With large number of work opportunities, the workforce has increased to a level where this has become an importance. Thus there needs to be a system that can handle the data of a large employee database as In today’s fast-changing business environment, it’s extremely important to be able to manage your employees and maintain a structure of hierarchy and records.
 

ABSTRACT
The main objective of this application is to make intended for tracking of employees and their information proficient and its ease of use. It would make searching, viewing and selection of an employee easier. This is a DBMS application intended for tracking of employees and their information. It contains a sophisticated search engine for managers to search for information specific to their needs. The process of constructing such kind of systems is not so simple. It involves a mutual development of application program and database. The application program is actually the bridge between the users and the database, where the data is stored. Thus, the well-developed application program and database are very important for the reliability, flexibility and functionality of the system.  

LIST OF ABBREVIATIONS
 

LIST OF TABLES




 1.Employee Information Table - Renu
2.Department Information Table - Parth
3.Employee Department Table - Abhinav
4.Employee Titles Table - Shivansh 
5.Employee Salary Table - Taha
6.Department Manager Table-Karthik





Table 1 - Employee Information Table
    emp_no      INT             NOT NULL,  -- UNSIGNED AUTO_INCREMENT??
    birth_date  DATE            NOT NULL,
    emp_name  VARCHAR(14)     NOT NULL,
    gender      ENUM ('M','F')  NOT NULL,  -- Enumeration of either 'M' or 'F'  
    hire_date   DATE            NOT NULL,
    PRIMARY KEY (emp_no)           


Table 2 - Department Information Table
a.Department Number - CHAR(4)
B. Department Name - VARCHAR(40)


Table 3 - Employee Department Table 
 Employee Number  INT(10),
Department Number   CHAR(4),
Starting date at the department   DATE,
Ending date at the department   DATE,
Number of projects completed  INT(3);

Table 4 - Employee Titles Table
a.	Employee Number - INT(10)    
b.	Employee Title - VARCHAR(50)
c.	Employee Title From date - DATE 
d.	Employee Title To date - DATE




Table 5 - Employee Salary Table
a.	Employee Number - INT(10) - PRIMARY KEY
b.	Employee Name - VARCHAR(255) 
c.	Department Number - INT(4) - FOREIGN KEY
d.	Monthly Salary - FLOAT(10,2)
e.	Annual Salary - FLOAT(10,2)
f.	Bonus - FLOAT(10,2)





Table 6 - Department Manager Table
a.	Employee Number - INT(10) - PRIMARY KEY
b.	Department Number - INT(4) Department Manager date – VARCHAR(40)

