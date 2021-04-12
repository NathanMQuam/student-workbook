# Day 49

Nathan Quam

---

[A Knight's Tail](https://github.com/NathanMQuam/A-Knights-Tail)

---
---

## Daily Journal

Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

1. In a SQL table, what is the difference between information in a row and information in a column?
`
A column is a definition for a value that all rows will have, like an ID or name. While a row is an individual object or group of related information, which contains the actual values for that object.
`

2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

```sql
CREATE TABLE characters
(
id INT NOT NULL UNIQUE,
name VARCHAR(255),
age VARCHAR(255),
description VARCHAR(255),

PRIMARY KEY (id)
);
```

1. What is the difference between the following statements:

```sql
DELETE FROM table_name;
DROP TABLE table_name;
```

`
The delete statement will completely remove the table "table_name" from the database. While the drop statement will remove all data and columns within the table "table_name", but the table will still be present in the database.
`
