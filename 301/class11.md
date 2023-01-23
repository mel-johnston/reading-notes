# Code 301 Reading Notes

[Class 1](https://mel-johnston.github.io/reading-notes/301/class1) -
[Class 2](https://mel-johnston.github.io/reading-notes/301/class2) -
[Class 3](https://mel-johnston.github.io/reading-notes/301/class3) -
[Class 4](https://mel-johnston.github.io/reading-notes/301/class4) -
[Class 5](https://mel-johnston.github.io/reading-notes/301/class5) -
[Class 6](https://mel-johnston.github.io/reading-notes/301/class6) -
[Class 7](https://mel-johnston.github.io/reading-notes/301/class7) -
[Class 8](https://mel-johnston.github.io/reading-notes/301/class8) -
[Class 9](https://mel-johnston.github.io/reading-notes/301/class9) -
[Class 10](https://mel-johnston.github.io/reading-notes/301/class10) -
[Class 11](https://mel-johnston.github.io/reading-notes/301/class11) -
[Class 12](https://mel-johnston.github.io/reading-notes/301/class12) -
[Class 13](https://mel-johnston.github.io/reading-notes/301/class13) -
[Class 14](https://mel-johnston.github.io/reading-notes/301/class14) -
[Class 15](https://mel-johnston.github.io/reading-notes/301/class15)

---

## Class 11 Notes - MongoDB, Mongoose and Data Modeling

### [SQL vs NoSQL](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/)

| SQL | NoSQL  |
|---|---|
| Relational Databases (RDBMS) | non-relational or distributed database |
| table based | document based, key-value pairs, graph or column |
| predefined schema | dynamic schema for unstructured data |
| SQL (structured query language) | UnSQL (unstructured query language) |
| MySQL, Oracle, Sqlite, Postgres, MS-SQL | MongoDB, BigTable, Redis, RavenDb, Cassandra |
| good for complex query | not good for complex query |
| not good for hierarchical data | good for heirarchical data |
| vertically scalable | horizontally scalable |
| heavy duty transactional based application | not suitable for high load and complex transactional applications |
| excellent support all databases | mostly community support |
| ACID properities (Atomicity, Consistency, Isolation, and Durability) | Brewers CAP theorem (Consistency, Availability, and Partition tolerance) |
| open-source or close-sourced from commercial vendors | stores data as graph databases, key-value store databases, document store databases, column store databases, and XML databases |
---

- What kind of data is a good fit for an SQL database?
  - MySQL database is very popular open-source database. It is generally been stacked with apache and PHP, although it can be also stacked with nginx and server side javascripting using Node js.
- What kind of data is a good fit a NoSQL database?
  - MongoDB stores data in JSON like documents.
- Which type of database is best for hierarchical data storage?
  - NoSQL
- Which type of database is best for scalability?
  - SQL

### [SQL vs NoSQL - Video](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

- What does SQL stand for?
  - structured query language
- What is a relational database?
  - database which works in a certain way and supports sql
- What type of structure does a relational database work with?
  - tables
- What is a ‘schema’?
  - which data can go into a table - fields (columns), records (rows)
- What is a NoSQL database?
  - NoSQL databases are the collection of key-value pair, documents, graph databases or wide-column stores
- How does it work?
  - the data do not have standard schema definitions which it needs to adhered to
- What is the disadvantage of a NoSQL database?
  - mostly community support, not good for complex query

#### Things I Want to Know More About