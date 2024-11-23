
### 1. Components of a DBMS (Database Management System)

A DBMS is software that helps store, manage, and organize data. The main components are:
 DBMS Engine: The software that interacts with the database.
 Database Schema: Defines the structure of the data (tables, columns, etc.).
 Query Processor: Interprets and executes the user’s requests (queries).
 Database Manager: Controls access to the database and handles transactions.
 Data Dictionary: A reference that holds metadata about the data (e.g., table structure).
 User Interface: Allows users to interact with the database using commands or a graphical interface.



### 2. What is a Relational Database? Give 4 Examples.

A relational database stores data in tables that are related to each other. Data is organized into rows and columns, and tables can be linked using keys.

Examples of relational databases:
 MySQL
 PostgreSQL
 Oracle Database
 Microsoft SQL Server



### 3. Three Classifications of SQL

SQL (Structured Query Language) can be classified into three types:
1. Data Definition Language (DDL): Defines the structure of the database (e.g., `CREATE`, `ALTER`, `DROP`).
2. Data Manipulation Language (DML): Manages data within the tables (e.g., `SELECT`, `INSERT`, `UPDATE`, `DELETE`).
3. Data Control Language (DCL): Controls access to data (e.g., `GRANT`, `REVOKE`).



### 4. Difference Between Primary Key and Foreign Key

 Primary Key: A unique identifier for each record in a table. It cannot be null and must be unique.
   Example: A student ID in a "Students" table.

 Foreign Key: A field in one table that links to the primary key of another table. It is used to establish a relationship between two tables.
   Example: The "student_id" in an "Enrollment" table that refers to the "student_id" in the "Students" table.



### 5. What is an EntityRelationship Diagram?

An EntityRelationship Diagram (ERD) is a visual representation of the entities (objects) in a database and how they are related to each other. It uses symbols to represent entities, attributes, and relationships. It's useful for designing databases.



### 6. Advantages of Relational Databases

 Data Integrity: Ensures data is accurate and consistent using constraints like primary keys and foreign keys.
 Easy to Use: Allows users to interact with data using SQL queries.
 Data Security: Restricts access to sensitive data with access control mechanisms.
 Flexibility: Can handle different types of data and relationships.
 Scalability: Can handle large amounts of data and can grow as needed.



### 7. Four Types of Data Types Used to Store Data in Tables

 INTEGER: Used to store whole numbers.
 VARCHAR: Used to store variablelength text or string values.
 DATE: Used to store date values (e.g., `YYYYMMDD`).
 DECIMAL: Used to store numbers with decimal points (e.g., for currency values).



### 8. Purpose of a Database Management System (DBMS)

The main purpose of a DBMS is to efficiently store, manage, and retrieve data. It helps:
 Organize data in a structured way.
 Allow users and applications to access data securely.
 Ensure data integrity and security.
 Manage large amounts of data efficiently.
 Support multiple users and control concurrent access to the database.
