# Day 52

Nathan Quam

---

[Afternoon Challenge](link.com)

---
---

## Daily Journal

Read Dotnet WebAPI's > Relationships, and answer the following questions

1. What is the difference between a primary key and a foreign key
`
A primary key is a UNIQUE identifier for a single row in a table, making it identifiable. While a foreign key does not uniquely identify a row, it does correlate to a row in another table, linking the two rows data together.
`

2. What is an Alias?
`
When performing a query, a table's columns may have names that are difficult to read, or not very descriptive of what they contain. An Alias renames the column only in the resulting table of data, letting it have a more readable/meaningful name.
`

3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

```sql
CREATE TABLE doctors (
id INT NOT NULL AUTO_INCREMENT,
name VARCHAR(255),
PRIMARY KEY (id)
);

CREATE TABLE patients (
id INT NOT NULL AUTO_INCREMENT,
name VARCHAR(255),
PRIMARY KEY (id)
);

CREATE TABLE appointments (
id INT NOT NULL AUTO_INCREMENT,
doctorId INT NOT NULL,
patientId INT NOT NULL,
PRIMARY KEY (id),
FOREIGN KEY (doctorId) REFERENCES doctors(id),
FOREIGN KEY (patientId) REFERENCES patients(id)
);
```

```sql
SELECT
a.id,
d.id AS DoctorId,
d.name AS DoctorName,
p.id AS PatientId,
p.name AS PatientName
FROM appointments a
JOIN doctors d ON d.id = a.doctorId
JOIN patients p ON p.id = a.patientId;
```
