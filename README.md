# sql-challenge

SQL Database Project
Overview
This project involves setting up and querying a database for managing employee and department data. It includes schema creation, data relationships, and various queries for retrieving employee information.

Project Structure
schema.sql: Contains SQL commands to create tables and define relationships for the database schema.
queries.sql: Contains SQL queries for retrieving data from the database, such as employee details, department lists, and frequency counts of last names.
Files
schema.sql: This file defines the database schema, including tables and constraints. Key tables include:

Files Included
ERD_Diagram.png: An image file representing the Entity-Relationship Diagram of the database, illustrating the relationships between tables.
table_schemata.sql: A SQL script that contains the CREATE TABLE statements needed to set up the database schema. This script includes definitions for tables like employees, salaries, titles, department, dept_emp, and dept_manager, with primary and foreign keys to establish relationships.
queries.sql: A SQL file containing various SQL queries to interact with the database, including SELECT, JOIN, and other data retrieval statements to answer specific business questions.


department: Stores department numbers and names.
employees: Stores employee information, such as employee number, name, title ID, birth date, sex, and hire date.
salaries: Stores salary information linked to employee numbers.
dept_emp: Associates employees with departments.
dept_manager: Associates managers with departments.
titles: Stores job title information.
Foreign key relationships are set up to enforce referential integrity between tables.

queries.sql: This file includes SQL queries for extracting useful data, such as:

List of all employees in each department.
Count of employees sharing the same last name.
Employee details filtered by criteria (e.g., hire date, department).
Setup
Database Creation: Ensure PostgreSQL or another SQL database system is installed and configured.
Schema Setup:
Run schema.sql to set up the database structure.
This will create tables, primary keys, and foreign key constraints.
Data Insertion:
Load data into the tables either by importing CSV files or by using INSERT commands.
Query Execution:
Run queries.sql to perform data retrieval operations.






