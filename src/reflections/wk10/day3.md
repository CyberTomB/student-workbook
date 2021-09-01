# Welcome to SQL (Week 10 Day 3)

## In a SQL table, what is the difference between information in a row and information in a column?

Information in a column are the "values" whereas a row contains the "classes" or "objects" that those values might be assigned to. For example, a "Player" object might have values like "Name, Health, Weapons" and SQL would store that information as a "Players" row, with "Name", "Health" and "Weapons" each as columns of those rows.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

```sql
CREATE TABLE characters(
  id int NOT NULL,
  name VARCHAR(25),
  age int,
  description VARCHAR(500)
)
```

## What is the difference between the following statements:
```sql
DELETE FROM table_name;
--ANSWER: This will delete all the data from the specified table without destroying the table itself. So the structure remains intact but is empty.

DROP TABLE table_name;
--ANSWER: This will delete the entire specified table, including the table structure itself. You will not be able to reference that table or its columns anymore.
```

### [Project Link](https://github.com/CyberTomB/csharp-kingdom)


