# Databases
With the help of ChatGPT and Techstarter this document will be filled


Some of the most common Databases (DB) are:
* Relational Databases, like MySQL, Oracle and SQL
* NoSQL Databases, like MongoDB, CouchDB and Cassandra
* Object-Oriented databases
* Time-Series databases, as InfluxDB and TimescaleDB
* Graph databases, as Neo4j and OrientDB
* Columnar databases, as Apache Cassandra or HBase
* Cloud databases, as AWS RDS or Azure SQL


### Relational Databases
##### Definition
A relational database is a type of database that organizes data into tables, which consist of rows and columns. 

Each table represents a set of related data, and each row in the table represents a unique instance of that data. 

The columns in the table represent the attributes or properties of the data.
##### Use
To interact with a relational database, you use a special language called **SQL (Structured Query Language)**

Here are a few commands for SQL:
> + SELECT - _retrieve data from table_
> + INSERT - _insert new data into table_
> + UPDATE - _update existing data in table_
> + DELETE - _delete data in table_
> + CREATE TABLE - _create new table in DB_
> + ALTER TABLE - _modify the structure of an existing table_
> + DROP TABLE - _delete a table from DB_


> Here is an example:
> > `SELECT * FROM students`
> This query will retrieve all data from the _students_ table
> **SQL** is case insensitive, though it is *best practices* to write all commands and names in **CAPITAL LETTERS**


### NoSQL Databases
Are DBs that store data in different models, such as:
+ **document**
+ **key-value**
+ **graph**

##### Document DBs
Store data as Documents, typically JSON or BSON format, where each document represents a single record with flexible schema
##### Key-Value Stores
Store data as a collection of *key-value pairs*, like a dictionary or hash-table. They are very fast and scalable, which makes them the prefered DB for caching, session-management and user preferences.
##### Graph DBs
Store data as *nodes* and *edges* in a graph, allowing for complex relationships to be modeled and queried.
> Need specialized knowledge and tools