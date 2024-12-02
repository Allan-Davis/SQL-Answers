<H2>1. State and Explain the components of a DBMS (Database Management System)</H2>

A **Database Management System (DBMS)** consists of several components that work together to manage and maintain databases efficiently. These components include:

- **Database Engine**: This is the core service for accessing and processing data. It is responsible for storing, retrieving, and updating data within the database.
- **Database Schema**: Defines the database structure, including the tables, fields, relationships, and constraints that organize the data.
- **Query Processor**: Interprets and processes SQL queries to interact with the database and retrieve or modify data.
- **Transaction Manager**: Ensures that transactions (a sequence of operations) are completed successfully and that data integrity is maintained by using techniques like ACID (Atomicity, Consistency, Isolation, Durability).
- **Data Dictionary**: Stores metadata (information about the structure and constraints of the data).
- **User Interface**: Provides access for users to interact with the database, typically via a command-line or graphical interface.
- **Security Manager**: Manages user permissions and access control to ensure that data is protected and accessible only by authorized users.



<H2>2. What is a relational database? Give 4 examples.</H2>

A **relational database** is a type of database that stores data in tables related to each other through keys (primary and foreign). Each table consists of rows (records) and columns (fields), where each row represents a unique record, and each column represents a specific attribute of the data.

**4 examples of relational databases**:
1. **MySQL**: An open-source relational database management system that uses SQL.
2. **PostgreSQL**: An advanced open-source relational database system known for its extensibility and standards compliance.
3. **Oracle Database**: A multi-model database management system developed by Oracle Corporation.
4. **Microsoft SQL Server**: A relational database management system developed by Microsoft for enterprise-level applications.



<H2>3. State and Explain three classifications of SQL</H2>

SQL (Structured Query Language) can be classified into the following categories:

- **DQL (Data Query Language)**: Used to query and retrieve data from databases. The most common DQL command is `SELECT`.
- **DML (Data Manipulation Language)**: Used to manipulate data within the database. It includes commands like `INSERT`, `UPDATE`, and `DELETE`.
- **DDL (Data Definition Language)**: Deals with the structure (schema) of the database. It includes commands like `CREATE`, `ALTER`, `DROP`, and `TRUNCATE` to define and modify tables and other database objects.


<H2>4. What is the difference between a Primary Key and a Foreign Key?</H2>

- **Primary Key**: A primary key is a field or combination of fields that uniquely identifies a record in a table. It must contain unique values and cannot have NULL values. Each table can have only one primary key.
- **Foreign Key**: A foreign key is a field or combination of fields in one table that links to the primary key in another table. It ensures referential integrity between the tables by ensuring that the value of the foreign key exists in the referenced table's primary key.


<H2>5. What is an Entity-Relationship Diagram?</H2>

An **Entity-Relationship Diagram (ERD)** visualises the entities (tables) in a database and their relationships. It shows how different entities (such as `Customers`, `Orders`, etc.) are connected to one another, along with the attributes (fields) of each entity. The diagram typically uses symbols to represent entities (rectangles), relationships (diamonds), and cardinality (lines connecting entities).


<H2>6. What are the advantages of relational databases?</H2>

- **Data Integrity**: Relational databases use constraints such as primary keys, foreign keys, and check constraints to ensure the accuracy and consistency of the data.
- **Flexibility**: Adding new tables or columns to a relational database is easy without affecting existing data.
- **Scalability**: Relational databases can efficiently handle large volumes of data and complex queries.
- **Security**: Access controls and user privileges can be set to protect data from unauthorized access.
- **Querying with SQL**: SQL provides a robust and standardized way to query, manipulate, and manage data.


<H2>7. State four types of data types used to store data in tables</H2>

1. **INT**: Used to store integer (whole number) values.
2. **VARCHAR**: Used to store variable-length string data.
3. **DATE**: Used to store date values (e.g., '2023-12-02').
4. **FLOAT**: Used to store floating-point numbers (decimal values).



<H2>8. What is the purpose of a database management system (DBMS)?</H2>

The primary purpose of a **DBMS** is to manage and organize the data within a database. It provides a systematic and efficient way to store, retrieve, and manipulate data while ensuring data integrity, security, and consistency. A DBMS also enables multiple users to access and interact with the database simultaneously, supports backup and recovery, and provides tools for data analysis and reporting.
