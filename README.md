# Database Design

### Agenda
- [] Primary Keys/Foreign Keys
- [] Naming Conventions
- [] Data Types
- [] Relationship Types
- [] Design Concepts
- [] Database Normalization
- [] Entity Relationship Diagrams
- [] ERD Examples

### Terminology

### RDBMS / RDB Engine
 - PostgreSQL
 - MySQL / MariaDB
 - Oracle
 - MSSQL

### Data
- Database - workspace
- Table - array of Object
- Rows / Records - objects
- Columns / Fields - string, numbers

 ### Keys / Indices / Index
  - identifiers
  - lookup records
  - multiple keys
  - book index
  - unique / duplicate
  - usually stored seperately
  - fast lookups

### Primary Key
  - unique
  - any data type - INTEGER / BIGINT
  - lookup

### Foreign Key
  - a primary key from another table
  - MUST be the same data type as the primary

### Naming Conventions
- Tables and Column snake_case
- Tables are always plural
- pimary key : `id`,
- foreign key: `animal_id`, `user_id`

### Data Types
  - Every field / column must have a data type

### SQL Standard
  - standard SQL data types
  - standard SQL syntax
  - Vendors add 'candy'. Avoid these
  - stick as close as you can to standard SQL types

### Relationships
 - one to one
 - one to many
 - many to many ** Does not exist! in RDB
 (2 - one to many )

 ### Entity Relationship Diagrams
 - The FK is on the Many side


 ### Scenario
 #### Jurassic Park

- People
- Dinosaurs

 Relationship between People and Dinosaurs
 ##### What is the intended Relationship between People and Dinosaurs?
 Many persons can View Many Dinosaurs

 #### What was the Actual Relationship between People and Dinosaurs?
 Many Dinoaurs can eat many people - bridge table attacks
