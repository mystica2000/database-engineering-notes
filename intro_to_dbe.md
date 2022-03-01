# Database System

##### Refresher: 
-   Tuple (single Row)
-   Relation (Table)
-   Primary Key (Uniquely Identify the tuple)
  
###### Primary Key
  - can be given manually
  - can auto-generated (AUTO_INCREMENT)

Datamodel - concept for describing data in the database.

Type of Datamodel
 - Relational 
 - Key/Value (NoSQL)
 - Graph (NoSQL)
 - Document (NoSQL)
 - Column-family (NoSQL)
 - Array/Matrix (Used in Machine Learning)
 - Network (obsolete/legacy)
 - Hierarchical (obsolete/legacy)


Relational Model ensures,
1. Structure (Tables)
2. Integrity (Primary Key/Foreign Key/etc)
3. Manipulation (DML)

n-ary Relation == table with "n" columns


DML (Data Manipulation Languages):

1.Procedural
-   high-level strategy the DBMS should use to find the desired result. (Relational Algebra)
 
2.Non-Procedural:
-   only what data is wanted and not how to find it. (Relational Calculus)

Relational Algebra:
    - based on set algebra
    - refer [this](http://www.mathcs.emory.edu/~cheung/Courses/377/Syllabus/4-RelAlg/intro.html) for the examples and operators.
    - primitive for processing queries on relational database.


Relational Calculas: 
    - Two types: domain and tuple. (will learn more about this later)
    - fundamental form of mathematical model for DML model. relational algebra can be mapped into relational calculas.
    - declarative (what i want to see only) 
  

Resources used:
 - [cmu database group](https://youtu.be/v4bU6n97Vr8?list=PLSE8ODhjZXjZaHA6QcxDfJ0SIWBzQFKEG)
 - [relational calculas](https://youtu.be/_oIuE1Pf4KM?t=2328)