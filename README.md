# Learn-SQL Resume

## Query
- A query is a question or a request for information expressed in a formal manner. In computer science, a query is essentially the same thing, the only difference is the answer or retrieved information comes from a database.

## CRUD

- Create : Insert statement 
- Read : Select statement 
- Update : Update statement 
- Delete : Delete statement 

## SQLite

- Every database system is different 
- Standard compliant
- Most predate standard 
- Sysntax may be different 
- Features may be missing 
- Non-standard features

## SQL Overview

### About SQL

#### SQL Statement 
- A statement is the unitive execution in SQL.
- Termineted with a semicolon(May not be required in all context, but it is a good pratice).
- An SQL statement often includes one or more clauses. 
```
SELECT * FROM Contries WHERE Continent = 'Europe';
```

- SQL is designed for a specific task: Operate and Manage a relational database

#### Database Organization

- The purpose of a database is to organize your data and to make it available in convenient forms.
- A relational database is organized in two-dimensional tables, comprised of rows and columms.
- A database has tables (One or more).
- A table has rows and collumns. 
- A row is like a record.
- A collumn is like a field. 
- Each row in a table has a unique key. The table's unique key may or may not correspond with a column in the table. A unique key identifies a table row. Sometimes the unique id is hidden, but the table must have one. 
- The primary key is simply means a column that is used as the unique key for this table. 
- The tables key is used to create relationship between tables. Tables are related by keys. 

#### The select Statement 

- The select statement returns results or a set of results from a query. 

#### The insert Statement

- Use the INSERT INTO statement to add rows a table.

#### Updating Data

- To change data in a table use the UPDATE statement. 

#### Delete Data

- Use DELETE FROM statement to delete rows from a table.

#### Create Table

- CREATE TABLE statement 

#### Delete Table

-  DELETE FROM statement

#### Insert Rows

- INSERT INTO statement

#### Delete Rows

- DELETE FROM statement

#### NULL Value

- NULL is a special state for a result with no value. It is important to distinguish between a zero or an empty string, or a non-value result. 

#### Constraining Columms

- As you are defining your schema you may want to define specific rules and behaviors for some os your columms. 

#### Changing a Schema 

- ALTER TABLE statement 

#### ID columm

- An ID columm is a columm that holds a unique value for each row in a table. Typically ID columns are automatically populated. 
- How you create id is different for each system. 

#### Filtering data

- OR, AND, LIKE, IN statement.

#### Remove duplicate

- SELECT DISTINCT statement 

#### Conditional Expression

- Somethign similar to switch case. 
- In Stadardized SQL, a zero is considered false and 1 true. 
