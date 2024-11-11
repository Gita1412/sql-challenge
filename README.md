# sql-challenge

SQL Database Project
Overview
This project involves setting up and querying a database for managing employee and department data. It includes schema creation, data relationships, and various queries for retrieving employee information.

# Files Included
ERD_Diagram.png: An image file representing the Entity-Relationship Diagram of the database, illustrating the relationships between tables.

table_schemata.sql: A SQL script that contains the CREATE TABLE statements needed to set up the database schema. This script includes definitions for tables like employees, salaries, titles, department, dept_emp, and dept_manager, with primary and foreign keys to establish relationships.

queries.sql: A SQL file containing various SQL queries to interact with the database, including SELECT, JOIN, and other data retrieval statements to answer specific business questions.

# Tables
department: Stores department numbers and names.

employees: Stores employee information, such as employee number, name, title ID, birth date, sex, and hire date.

salaries: Stores salary information linked to employee numbers.

dept_emp: Associates employees with departments.

dept_manager: Associates managers with departments.

titles: Stores job title information.

Foreign key relationships are set up to enforce referential integrity between tables.







