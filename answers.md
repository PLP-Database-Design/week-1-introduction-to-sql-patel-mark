## 1. Components of a DBMS (Database Management System)
The key components of a DBMS are:

Database Engine: Handles data storage, retrieval, and updates. It translates queries into low-level instructions to manage the database.
Data Definition Language (DDL): Provides tools for defining the database schema (structure), such as creating, modifying, and deleting tables.
Data Manipulation Language (DML): Enables users to interact with and manipulate the data, such as querying, updating, inserting, and deleting records.
Database Schema: The logical structure that defines how the database is organized, including tables, fields, relationships, and constraints.
Query Processor: Interprets and executes SQL queries submitted by users or applications.
Transaction Management: Ensures consistency, isolation, and recovery of the database during transactions.
Data Storage Management: Manages how data is stored on physical storage devices and ensures efficient storage and retrieval.
Security Management: Enforces security policies to restrict unauthorized access and protect data integrity.
## 2. What is a Relational Database? Give 4 Examples.
A relational database is a type of database that stores data in tables (rows and columns) with predefined relationships between the tables. Data is structured, and relationships are maintained through keys like primary keys and foreign keys.

Examples:
MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
## 3. Classifications of SQL
SQL is classified into three main categories:

Data Definition Language (DDL): Deals with the structure of the database (schema).
Commands: CREATE, ALTER, DROP, TRUNCATE
Example: CREATE TABLE employees (id INT, name VARCHAR(50));
Data Manipulation Language (DML): Used for managing data within tables.
Commands: INSERT, UPDATE, DELETE, SELECT
Example: INSERT INTO employees (id, name) VALUES (1, 'John');
Data Control Language (DCL): Manages permissions and access to the database.
Commands: GRANT, REVOKE
Example: GRANT SELECT ON employees TO user1;
## 4. Difference Between Primary Key and Foreign Key
Primary Key:
Uniquely identifies each row in a table.
Cannot contain NULL values.
Ensures the table's data integrity.
Example: id column in an employees table.
Foreign Key:
Establishes a relationship between two tables.
References the primary key in another table.
Can have duplicate values and NULL in some cases.
Example: department_id in an employees table referencing the id in a departments table.
## 5. What is an Entity-Relationship Diagram (ERD)?
An ERD is a visual representation of entities (data objects) and their relationships within a database. It helps in database design by depicting:

Entities (e.g., tables like customers or orders).
Attributes (columns, like name, address, etc.).
Relationships (e.g., one-to-one, one-to-many, or many-to-many).
## 6. Advantages of Relational Databases
Data Integrity: Enforces data accuracy and consistency through constraints.
Scalability: Can handle large volumes of structured data.
Ease of Use: SQL simplifies data retrieval and management.
Data Security: Includes features like role-based access and encryption.
Relationships: Supports linking data across multiple tables for complex queries.
## 7. Four Data Types Used to Store Data in Tables
INTEGER: Stores whole numbers (e.g., 10, 25).
VARCHAR: Stores variable-length strings (e.g., names, email addresses).
DATE: Stores date values (e.g., 2024-11-30).
BOOLEAN: Stores true/false values.
## 8. Purpose of a Database Management System (DBMS)
The purpose of a DBMS is to provide a systematic way to store, retrieve, manage, and secure data efficiently. Key objectives include:

Facilitating data storage and retrieval.
Supporting multiple users simultaneously.
Ensuring data integrity and consistency.
Providing security and controlled access.
Supporting data analysis and reporting.
Reducing data redundancy and maintaining efficient storage.