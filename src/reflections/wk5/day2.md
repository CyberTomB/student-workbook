# Relationships (Week 5 Day 2)

## What are the three types of relationships?

1:1, 1:M, N:M (one to one, one to many, and many to many)

## What are the benefits of the traditional linking of relationstionships instead of Embedding?

Embedding related objects can lead to very lengthy read/write times for the database, as well as exceeding our maximum sizes for the partitions of the DB. By linking the relationships instead, we can read/write with more specificity and keep data partitioned and the size of our data within desireable ranges.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

The challenge comes in the form of the nature the relationships have and how many objects they may be referencing in one direction versus the other. To help decide the best way to manage the relationships, we should consider the relative size and scope of the references.