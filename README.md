# Advanced SQL Project

## Overview

This project focuses on advanced SQL concepts and practices. The aim is to deepen the understanding of MySQL by exploring topics such as table creation, query optimization, stored procedures, functions, views, and triggers.

## Learning Objectives

By the end of this project, you should be able to explain the following concepts:

- How to create tables with constraints.
- How to optimize queries by adding indexes.
- What stored procedures and functions are and how to implement them in MySQL.
- What views are and how to implement them in MySQL.
- What triggers are and how to implement them in MySQL.

## Resources

To assist you in this project, refer to the following resources:

- [MySQL Cheatsheet](https://www.example.com)
- [MySQL Performance: How to Leverage MySQL Database Indexing](https://www.example.com)
- [Stored Procedure](https://www.example.com)
- [Triggers](https://www.example.com)
- [Views](https://www.example.com)
- [Functions and Operators](https://www.example.com)
- [Trigger Syntax and Examples](https://www.example.com)
- [CREATE TABLE Statement](https://www.example.com)
- [CREATE PROCEDURE and CREATE FUNCTION Statements](https://www.example.com)
- [CREATE INDEX Statement](https://www.example.com)
- [CREATE VIEW Statement](https://www.example.com)

## Requirements

### General

- All your files will be executed on **Ubuntu 18.04 LTS** using **MySQL 5.7** (version **5.7.30**).
- All your files should end with a new line.
- All your SQL queries should have a comment just before (i.e., syntax above).
- All your files should start with a comment describing the task.
- All SQL keywords should be in **UPPERCASE** (e.g., SELECT, WHERE).
- A `README.md` file, at the root of the project folder, is mandatory.
- The length of your files will be tested using `wc`.

### Comments for your SQL file

Use comments to describe your SQL scripts. For example:

```sql
-- 3 first students in the Batch ID=3
-- because Batch 3 is the best!
SELECT id, name FROM students WHERE batch_id = 3 ORDER BY created_at DESC LIMIT 3;

$ service mysql start
 * MySQL Community Server 5.7.30 is started

$ echo "CREATE DATABASE hbtn_0d_tvshows;" | mysql -uroot -p
Enter password: 
$ curl "https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/274/hbtn_0d_tvshows.sql" -s | mysql -uroot -p hbtn_0d_tvshows
Enter password: 
$ echo "SELECT * FROM tv_genres" | mysql -uroot -p hbtn_0d_tvshows
Enter password: 

