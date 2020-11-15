## Data

###### Data is a collection of a distinct unit of information. This “data” is used in a variety of forms of text, numbers, media and many more.Data is basically information that can be translated into a particular form for efficient movement and processing.

## Database

###### The database is an organized collection of structured data to make it easily accessible, manageable and update. In simple words, you can say, a database in a place where the data is stored. The best analogy is the library. The library contains a huge collection of books of different genres, here the library is database and books are the data.Databases are developed using fixed design and modeling approaches.

## DBMS

###### A Database Management System (DBMS) is a software that is used to manage the Database. It receives instruction from a Database Administrator (DBA) and accordingly instructs the system to make the corresponding changes. It is a system software responsible for the creation, retrieval, updation and management of the database. It ensures that our data is consistent, organized and is easily accessible by serving as an interface between the database and its end users or application softwares.

## DELETE vs DROP vs TRUNCATE

- DELETE is a DML command. DELETE statement is used to delete rows from a table, keeping the table structure alive.Rollback can be used after DELETE to go back the last commited state or savepoint.

- DROP is DDL command.DROP command is used to remove an object from the database. If you drop a table, all the rows in the table is deleted and the table structure is removed from the database.No Rollback possible.

- TRUNCATE is DDL command.TRUNCATE command is used to delete all the rows from the table,keeping the table structure alive. Since ** DDL command includes implicit commit **, so there is no way of Rollback.
