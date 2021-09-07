# C# Relationships

## What is the difference between a primary key and a foreign key?

A primary key is a unique identifier for an object within a table, it is only referenced by one data set. A foreign key is a reference a data object might make to an outside table's primary key. 

## What is an Alias?

An alias is a replacement name for a table name that can be declared following the first instance of the full table name. This way, you can write the alias instead of spelling out the entire table name each time.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

```sql
CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctorsPatients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)
```
### *ANSWER:*
```sql
SELECT * FROM doctorsPatients dp
JOIN patients p ON p.id = dp.patientId;

```

### [Project Link](https://github.com/CyberTomB/csharp_contractors)