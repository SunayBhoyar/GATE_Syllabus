# GATE Databases Preparation Checklist

## 1. **Entity-Relationship (ER) Model**
- [ ] **Basic Concepts of ER Model**
  - [ ] Entities, Entity types, and Entity sets
  - [ ] Attributes: Simple, composite, multivalued, derived, and key attributes
  - [ ] Relationships: Relationship types, sets, and degree
  - [ ] Weak entities and identifying relationships
- [ ] **Advanced ER Concepts**
  - [ ] Generalization, Specialization, and Aggregation
  - [ ] Generalization hierarchy
  - [ ] ER diagram notation and symbols
  - [ ] Mapping ER models to relational schemas

## 2. **Relational Model**
- [ ] **Basic Concepts of Relational Model**
  - [ ] Relation, tuple, and attributes
  - [ ] Domain and degree of relations
  - [ ] Keys: Primary, candidate, super, foreign
  - [ ] Relational schema and instance
- [ ] **Relational Algebra**
  - [ ] Select, Project, Union, Set Difference, Cartesian Product
  - [ ] Join operations: Inner, outer, natural join
  - [ ] Division, intersection, and renaming operations
  - [ ] Aggregate functions: COUNT, SUM, AVG, MIN, MAX
- [ ] **Tuple Relational Calculus**
  - [ ] Syntax and semantic of tuple relational calculus
  - [ ] Query formulation using tuple calculus
  - [ ] Comparison of tuple relational calculus with relational algebra
- [ ] **Domain Relational Calculus**
  - [ ] Syntax and semantics of domain relational calculus
  - [ ] Query formulation using domain calculus

## 3. **SQL (Structured Query Language)**
- [ ] **SQL Basics**
  - [ ] SQL Data Types: CHAR, VARCHAR, INT, DATE, etc.
  - [ ] DDL (Data Definition Language): CREATE, ALTER, DROP
  - [ ] DML (Data Manipulation Language): SELECT, INSERT, UPDATE, DELETE
  - [ ] DCL (Data Control Language): GRANT, REVOKE
  - [ ] TCL (Transaction Control Language): COMMIT, ROLLBACK, SAVEPOINT
- [ ] **SQL Queries**
  - [ ] Single-table queries
  - [ ] Multi-table queries with JOIN (INNER, LEFT, RIGHT, FULL OUTER)
  - [ ] Subqueries (nested queries): IN, EXISTS, ANY, ALL
  - [ ] Grouping data with GROUP BY, HAVING
  - [ ] Sorting and filtering with ORDER BY, DISTINCT, LIKE, BETWEEN, etc.
  - [ ] Set operations: UNION, INTERSECT, EXCEPT
  - [ ] Views and indexes in SQL
  - [ ] Transaction control in SQL
- [ ] **SQL Constraints**
  - [ ] Primary Key, Foreign Key, Unique, Not Null, Check
  - [ ] Referential integrity constraints
  - [ ] ASSERTION and TRIGGERS

## 4. **Integrity Constraints**
- [ ] **Types of Integrity Constraints**
  - [ ] Domain constraints (validity of data types)
  - [ ] Key constraints (primary and foreign keys)
  - [ ] Entity integrity (primary key constraint)
  - [ ] Referential integrity (foreign key constraint)
  - [ ] Semantic integrity constraints (custom business rules)
- [ ] **Ensuring Data Integrity**
  - [ ] Cascade updates and deletes
  - [ ] Deferred constraints enforcement
  - [ ] Default values and NOT NULL constraints

## 5. **Normalization**
- [ ] **Normalization Basics**
  - [ ] Redundancy and its problems (update, delete, insert anomalies)
  - [ ] Functional dependencies and their role in normalization
- [ ] **Normal Forms**
  - [ ] First Normal Form (1NF): Atomicity of attributes
  - [ ] Second Normal Form (2NF): Elimination of partial dependencies
  - [ ] Third Normal Form (3NF): Elimination of transitive dependencies
  - [ ] Boyce-Codd Normal Form (BCNF): Stronger version of 3NF
  - [ ] Fourth Normal Form (4NF): Elimination of multi-valued dependencies
  - [ ] Fifth Normal Form (5NF): Elimination of join dependencies
- [ ] **Denormalization**
  - [ ] Trade-offs between normalization and denormalization
  - [ ] When and how to denormalize for performance optimization

## 6. **File Organization**
- [ ] **File Organization Techniques**
  - [ ] Heap (Unordered) file organization
  - [ ] Sequential file organization
  - [ ] Indexed file organization
  - [ ] Hashing file organization
- [ ] **Primary and Secondary Indexes**
  - [ ] Dense and sparse indexes
  - [ ] Multilevel indexing
  - [ ] Index structures: B-trees, B+ trees
- [ ] **Hashing Techniques**
  - [ ] Static hashing and dynamic hashing
  - [ ] Hash collisions and resolution strategies
  - [ ] Extendible hashing and linear hashing

## 7. **Indexing**
- [ ] **Indexing Basics**
  - [ ] Index types: Primary, secondary, clustering
  - [ ] Single-level and multi-level indexing
- [ ] **B-Trees and B+ Trees**
  - [ ] Characteristics and structure of B-trees
  - [ ] Insertion, deletion, and search operations in B-trees
  - [ ] Difference between B-tree and B+ tree
  - [ ] B+ tree indexing, its advantages in database indexing
- [ ] **Other Indexing Techniques**
  - [ ] Bitmap indexing, hash indexing, and clustered indexing
  - [ ] Multi-dimensional indexing (e.g., R-trees)

## 8. **Transactions and Concurrency Control**
- [ ] **Transactions**
  - [ ] ACID properties (Atomicity, Consistency, Isolation, Durability)
  - [ ] Transaction states (Active, Partially committed, Failed, Committed, Aborted)
- [ ] **Transaction Management**
  - [ ] Transaction log (Write-ahead log protocol)
  - [ ] Undo and redo operations
- [ ] **Concurrency Control**
  - [ ] Locks: Shared, exclusive locks, and lock types (binary, intention)
  - [ ] Two-phase locking protocol
  - [ ] Deadlock detection and prevention
  - [ ] Timestamp-based concurrency control
  - [ ] Optimistic concurrency control
- [ ] **Recovery**
  - [ ] Log-based recovery
  - [ ] Checkpointing
  - [ ] Shadow paging

