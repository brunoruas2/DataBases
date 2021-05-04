## Book - SQL Coding for Begginers by Leonard Base

<details open>
<summary>
<h1> Abbreviation summary </h1>
</summary>

<br />

> SQL - Structured Query Language

> DBMS - Database Management System

> OLTP - Transaction Oriented Applications

</details>

<details open>
<summary>
<h1> Chapter 01 - Intro to SQL and Data Definition Language </h1>
</summary>

<br />

- [ ] A
  - [x] b

There are four groups of features that most of DBMS currently offer:
 - Data Definition
 - Update
 - Retrieval
 - Management (user registration and security stuff)

A **database system** is made by a *database (storage)*, a *DBMS* which are in accordance with some *model database*.

A **database server** is a computer wich only run DBMS and some other relaterd softwares which the primary job is to hold real databases.

Databases and DBMS can have some parameters like:
- supported database models (relational or XML)
- how much computers can operate than (like clusters)
- query language (SQL or XQuery)
- internal engineering

Here we will focus on **relational databases**. This type of database consist of a "collection of tables" that can be matched to a predetermined category and each table has at least one **data category** in a column and each row has a certain **data instance**.

## Types o SQL Queries (also called Sublanguages)
- Data Definition Language (DDL)
  - creation of tables
  - alteration of tables
  - elimination of tables
  - relationships of tables
- Data Manipulation Language (DML)
  - insert a row
  - update a row
  - deletion a row
  - lock a row
  - merge a row
- Data Control Language (DCL)
  - grant acces to some users
  - revoke a acces to some users
- Data Query Language (DQL)
  - select a content in database
- Transaction Control Language (TCL)
  - rollback a update to cancel it
  - commit a update to save it
  - savepoint to create a milestone of the data

## SQL Syntax hints
1. Use a semicolon `;` in the end of each command
1. A keyword must be used in the beginning of each command
1. SQL is not case sensitive

## SQL Data Types

| Data Type      | Description                                |
|----------------|--------------------------------------------|
| char(size)     | fixed length char string. Max 255chards    |
| varchar(size)  | max length char string                     |
| number(size)   | max numbers allowed                        |
| date           |                                            |
| number(size,d) | max numbers and the number of decimal part |
| int            | an interger                                |

## Data Definition Language (DDL) - Commands
- CREATE
  - Usage:
    - Create Databases and Tables
    - tends to be the 1º step
  - Syntax:
    - `CREATE DATABASE database_name`
    - `CREATE TABLE table_name1`
    - `CREATE TABLE table_name2 (column1 datatype, column2 datatype ...)`
- ALTER
  - Usage:
    - add a column
    - remove a column
    - add different data constraints
    - remove already saved data constraints
  - Some Data Constraints:
    - NOT NULL
    - UNIQUE
    - PRIMARY KEY
    - FOREIGN KEY
    - CHECK
    - DEFAULT
    - INDEX
  - Syntax:
    - PAREI AQUI PAGINA 18
- RENAME
- DROP
- TRUNCATE

</details>

<details>
<summary>
<h1> All subjects to be learned </h1>
</summary>

<br />

**Chapter 01**
- [x] The different types of database management systens and their advantages
- [ ] The 5 Fundamental types of SQL queries
  - DDL - Data definition language
  - DML - Data manipulation language
  - DCL - Data control language
  - DQL - Data query language
  - TCL - Transaction control language
- [ ] The most used data types
- [ ] SQL CREATE
- [ ] SQL ALTER

**Chapter 02**
- [ ] Installing MySQL in SO
- [ ] Temporary tables
- [ ] Derived tables
- [ ] How to create a table from another already presente in database

**Chapter 03**
- [ ] SQL SELECT
- [ ] ORDER BY
- [ ] WHERE
- [ ] SQL JOIN
  - INNER
  - LEFT
  - RIGHT
  - CROSS
  - SELF
- [ ] SQL UNION and UNION ALL

**Chapter 04**
- [ ] Database View
- [ ] CREATE VIEW
- [ ] MERGE
- [ ] TEMPTABLE
- [ ] UNDEFINED
- [ ] Updatable SQL Views
- [ ] ALTER VIEW
- [ ] CREATE OR REPLACE VIEW
- [ ] START TRANSACTION
- [ ] COMMIT
- [ ] ROLLBACK
- [ ] SQL BACKUP

**Chapter 05**
- [ ] Access privileges
- [ ] Create new users accounts

</details>
