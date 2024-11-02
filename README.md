
# LITA-training- program 

### project title: Data analysis
---
[project overview](#project-overview)

[Data sources](#data-sources)

[Tools used](#tools-used)

[Data cleaning and preparations](#data-cleaning-and-preparations)

[Exploratory data analysis](#exploratory-data-analysis)

[Introduction to excel](#introduction-to-excel)

[Basic functions in excel](#basic-functions-in-excel)

[Data entry in excel](#data-entry-in-excel)

[Data analysis](#data-analysis)

[Data description](#data-description)

[Data fields](#data-fields)

[Data visualization](#data-visualization)

[Introduction to SQL](#introduction-to-SQL)

[What are SQL](#what-are-SQL)

[what is databases](#what-is-databases)

[Advantage of databases](#advantage-of-databases)

[Why SQL](#why-SQL)

[SQL command](#SQL-command)

[Types of SQL commands](#types-of-SQL-commands)

[Microsoft SQL server](#microsfoft-SQL-server)

[SQL server management studio](#SQL-server-management-studio)

### project overview
Data analysis is the process of examining, cleaning, and interpreting data to extract useful insights and support decision-making. It involves collecting data from various sources, cleaning it to ensure accuracy, and then using techniques like exploratory data analysis (EDA) to identify patterns and trends. Advanced methods, such as statistical analysis and machine learning, can then be applied for deeper insights. Overall, data analysis is essential in various fields to help organizations make informed, data-driven decisions.

### Data sources
---
The primary source of data used is from Kaggle, which is a great platform that offers a wide variety of datasets across different domains. It’s a valuable resource for data analysis projects, providing access to real-world data and allowing me to explore various data science techniques.

### Tools used
---
- microsoft excel [download here](https://www.microsoft.com)
  1. for data cleaning
  2. for analysis
  3. for data visualization
- SQL-structured query language for querying of data
- github for portfolio building

### Data cleaning and preparations
---
1. data loading and inspection
2. handling missing variables
3. data cleaning and formatting
   

### Exploratory data analysis
---
EDA is essential for gaining insights into the data before applying more complex statistical methods or machine learning algorithms.
- Exploratory Data Analysis summarize the main characteristics of a dataset through descriptive statistics.
- It visualizes data patterns and relationships using various charts and graphs.
- what are the overall sales trend?
- what product are the top sellers?
- what are product on peak sales?


### Introduction to Excel
---
Microsoft Excel is a powerful spreadsheet application that is part of the microsoft office suite. it is widely used for organizing,analyzing and visualizing data. Excel allows users to create spreadsheets that consist of rows and columns, making it easy to input and manage large amount of data

### Basic Excel functions 
---
1. Sum: This function adds up a range of numbers. The syntax: ```=SUM(number1,number2....) or sum(range)```
2. Average: This function calculates the mean of a set of numbers. The syntax: ```=Average(number1,number2....) or Average(range)```
3. Min: This function returns the smallest number in a range. The syntax: ```=Min(number1,number2...) or Min(range)```
4. Max: This fuction returns the kargest number in a range. The syntax: ```=Max(number1,number2....)```
5. Concatenate: This function joins two or more strings together.The syntax: ```=Concatenate(number1,number2...)```
7. Count: This function is used to count figures in excel. The syntax: ```=Count(number1,number2...)```
9. Counta: This function is used to count alphabets in excel. The syntax: ```=Counta(number1,number2.....)```
10. ![ecelll real](https://github.com/user-attachments/assets/7a9f6b08-13ea-4ab8-a283-3310921b08a9)

  
11. Conditional functions in excel are powerful tools that allow you to perform calculations or return values based on specific confit. here are some of the most commonly used conditional functions:
- IF function : ```=if(logical_test,value_if_true,value_of_false)```
- Sumif : ```=sumif(range,criteria,{sum_range})```
- Averageif: ```=averageif(range,criteria,{average_range})```
- countif:``` =countif(range,criteria)```
![excel 22](https://github.com/user-attachments/assets/6aa033bb-1364-4d87-b252-d53be7f1be1d)

### Data entry in excel
---
Data entry in excel is refer to a process of inputting, organizing and managing data within an excel spreadsheet 

### Data description 
---
The dataset provides information about the following 
- sale transaction 
- Enabling Analysis of sales performance across different regions,markets,stores,products and time periods

### Data fields
---
1. Region
2. Market 
3. Store
4. Trade date
5. Model
6. Day Category 
7. Unit Sold
8. Trade date

### Data visualization 
---
Data visualization using pivot tables in excel is a powerful way to summarize and analyze large datasets. The steps in using to create a pivot table 

step 1: Prepare your data.
step 2: create a pivot table
- select your data
- insert pivot table: Go to the insert tab in the excel ribbon, click on pivot table
- choose the data then click ok
![PIVOT PROOF](https://github.com/user-attachments/assets/03f09a8f-3907-4263-9316-0bc62f9a1007)


### INTRODUCTION TO SQL
-----
SQL- Structured Query Language 
It is a standardized programming language used for managing and manipulating relational databases. it allows user to perform various operations on data, including querying, updating, inserting and deleting records. SQL allows user to query the database in a number of ways, using English-like statements 

### what are SQL?
SQL follows the following rules:
- structured query language is not case sensitive
- statements of SQL are dependent on text lines. we can use single SQL statement on one or multiple text line.
- SQL depends on tuple relational calculus and relational algebra 

### what is databases
---
A database is an organized collection of data that is stored and managed in a structured way to allow for east access,retrieval and manipulation.

### Advantage of Databases:
1. Data integrity
2. Security 
3. Backup and Recovery 
4. Concurrency
5. Scalability 
6. Efficient Data Management 

### Why SQL
---
- SQL is easy to understand.
- Traditional databases allow us to access data directly 
- Traditional databases allow us to adult and replicate our data
- SQL is a great tool for analyzing multiple tables at once
- SQL allows you to analyze more complex questions than dashboard tools

### SQL Commands
---
SQL commands are instructions. it is used to communicate with the database.it is also used to perform specific tasks,functions and queries of data
SQL can perform various tasks like create a table, add data to tables, drop the table,modify the tablr, set permission for isers

### Types of SQL Commands
---
There are five types of SQL commands
1. DDL: Data Definition Language( create,alter,drop,truncate )
2. DML: Data Manipulation Language (insert,update,delete)
3. DCL: Data Control Language ( grant,revoke)
4. TCL: Transaction Control Language(commit,delete,update)
5. DQL: Data Query Language ( select)

### Microsoft SQL server 
---
Microsoft SQL server is a relational database management system developed by Microsoft to store and retrieve data as requested by other software applications 

### SQL Server Management Studio
---
This is a software application developed by Microsoft that is used for configuring, managing and administering SQL setver databases. it provides a graphical interface for interacting eith SQL server databases and performing various tasks such as:
1. Database Development 
2. Database Administration
3. Querying Data
4. Import and Export data

### writing queries in SQL
---
writing queries in SQL is essential for managing and manipulating relational databases.SQL is a case-insensitive, but it is common practice to write keyboards in uppercase.

Select statement:This is used to retrieve data from one or more tables. 
syntax: 
```sql
SELECT column1,column2 from
table_name
```

where clause:This filters records that meet specific conditions.
syntax:
```sql
select column1,column2 from
table_name WHERE condition
```

Delete statement:This removes records from a table.
syntax:
```sql
DELETE from table_name 
where condition
```

Insert into statement: This adds new records to a table.
syntax:
```sql
INSERT INTO table_name(column1,column2)
VALUES(value1,value2)
```

Order by clause:This sorts the result set in ascending or descending order
syntax
```sql
SELECT column1,column2 from
table_name ORDER BY column1 asc/desc
```
### To create a table on SQL
---
![sql proof](https://github.com/user-attachments/assets/3a2f7969-8619-43af-a527-1af9e28c066c)

1. create a table

```sql
create database LITA_DB
```

2. create Employee table

```sql
create table employee (
staffid varchar (255) not null,
firstname varchar (255) not null,
secondname varchar (255),
gender varchar (10),
date_of_birth date,
hiredate datatime
primary key (staffid)
)
```

3. Select: help to retrieve information 

```sql
select * from employee
```

4. insert: to put in the database on the table

```sql
insert into employee 
(staffid,firstname,secondname,gender,date_of_birth,hiredate)
```

### Power BI
Power BI is a Business analytics tools developed by Microsoft that ensbles users to visualize data and share insight across their organization or embed in an app or website, it allows users to connect to various data sources, transform raw data into interactive dashboards and reports, perform data Analysis with ease

### Data sources for Power BI
Power BI support wide variety of data sources that can connect to for reports and dash boards
1. Excel
2. SQL server
3. Cloud services
4. Web data
5. Csv files



  
  

