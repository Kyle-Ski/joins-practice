# Intro to SQL Joins

## Objectives

* Explain the order & structure of join statements
* Write basic SQL joins: `one-to-many`
  - INNER join
  - LEFT join
  - FULL OUTER join
* Write basic SQL joins that only select certain fields
  - INNER join
  - LEFT join

## Instructions

1. Create a database called joins
2. Connect to joins database using psql
3. Run joins.sql file while connected to db:
  - `\i joins.sql`

## Resources

* [Learn - Joins Syntax](https://github.com/gSchool/sql-curriculum/blob/master/Joins.md#joins---syntax)
* [Visual Representation of SQL Joins](https://www.codeproject.com/Articles/33052/Visual-Representation-of-SQL-Joins)

# SQL Joins: Many-to-Many

## Objectives

* Write many-to-many SQL joins
  - INNER JOIN all fields
  - INNER JOIN selected fields
  - INNER JOIN selected fields with aliases
* Write many-to-many SQL joins that return subsets of data
* Explain syntax and structure of many-to-many SQL joins

## Instructions

1. Create a database called many-joins
2. Connect to many-joins database using psql
3. Run joins.sql file while connected to db:
  - `\i many-joins.sql`

## Notes

* INNER JOIN all fields

* INNER JOIN selected fields
  - author name
  - author email
  - book title

* INNER JOIN selected fields with aliases
  - author id (aliased)
  - author name
  - book id (aliased)
  - book title

* INNER JOIN subset of data
  - All fields for 'Mark' and his book(s)

* INNER JOIN subset of data
  - All fields for 'Modern Romance' and its author(s)