# Learn-SQL

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
