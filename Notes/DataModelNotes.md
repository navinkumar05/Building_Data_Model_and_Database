# Data Model

## Basics of Data model

### what is data model?

A data model is an abstract model that **organizes elements of data** and standardizes **how they relate to one another** and to the properties of real-world entities.

<img src ="attachments\DataModel.jpg" width=600>

### Why is Data Modeling Important?

- A data model is like a blueprint for organizing information in a database.
- It helps in understanding how data relates to each other.
- It guides how data should be stored and accessed.
- Without a data model, managing and using data would be messy and disorganized.
- So, a data model is essential for keeping data organized, consistent, and easy to work with.

### Who Does This Type of Work?

- Data Scientist
- Software Engineers
- Data Engineers
- Anyone involved in the process of using and analyzing data

### Relational Model and Database

Organizes data into one or more tables of columns and rows, with a unique key identifying each row.

<img src ="attachments\relational-dbms-model.png" width=600>

#### Database/Schema

- Collection of Tables
  
#### Tables/Relations

- A group of rows sharing the same labeled elements.
  - Students
  - Subjects
  - Marks

#### Advantages of using a Relational Database

- Ease of use - SQL
- Ability to do JOINS
- Ability to do aggregations and analytics
- Smaller Data Volumes
- Flexibility of queries
- ACID transactions - data integrity

### ACID Properties

[ACID_Blog](https://notes123.hashnode.dev/acid-properties)

#### When to not use Relational Database

- Large amounts of Data
- Need to be able to store different data types formats
- Need a flexible schema
- Need high availability
- Need horizontal scalability

## Exercise 1 - Creating Tables in Postgres using python
