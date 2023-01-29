# Activity - SQL STATEMENTS

Use SQL statements to do the following: 

Create a table called users with the following schema 
```
user_id - SERIAL PRIMARY KEY This should autoincrement and should be primary key 

first_name - VARCHAR(50) 

last_name - VARCHAR(50) 

is_employee - BOOL (default is true) 

date_created - TIMESTAMP DEFAULT current_timestamp 

date_updated - TIMESTAMP DEFAULT current_timestamp
```
 

- Insert 3 records into the users table (two where isemployee = true and one where isemployee is false) 

- Select all records from the users table 

- Select all records where isemployee is true 

- Sort the records in decending order based on datecreated  
