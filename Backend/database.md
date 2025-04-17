
# 🗄️ Database Roadmap:

---

## 🍃 MongoDB (NoSQL)

### 🔹 1. Introduction to MongoDB
- What is MongoDB?
- NoSQL vs SQL (Key Differences)
- MongoDB Structure: Databases, Collections, Documents
- Installing MongoDB locally or using Atlas
- Compass vs CLI vs Drivers (e.g., Node.js)

---

### 🔹 2. MongoDB Basics
- Creating Databases & Collections
- Inserting Documents (`insertOne`, `insertMany`)
- Querying Documents (`find`, filters, projections)
- Updating Documents (`updateOne`, `updateMany`)
- Deleting Documents (`deleteOne`, `deleteMany`)

---

### 🔹 3. Query Operators & Filtering
- Comparison: `$gt`, `$lt`, `$eq`, `$ne`, etc.
- Logical: `$and`, `$or`, `$not`, `$nor`
- Array: `$in`, `$nin`, `$all`, `$elemMatch`
- Field existence: `$exists`, `$type`

---

### 🔹 4. Working with Embedded Data
- Embedding vs Referencing
- Querying nested documents
- Dot notation

---

### 🔹 5. Indexing & Performance
- Creating Indexes
- Types: Single Field, Compound, Text, Geo
- `explain()` method for query performance
- TTL Indexes

---

### 🔹 6. Aggregation Framework
- `$match`, `$group`, `$sort`, `$project`, `$limit`, `$skip`
- `$lookup` (Join-like operations)
- Pipelines & stages
- Aggregation vs MapReduce

---

### 🔹 7. Schema Design & Validation
- Schema Best Practices
- Data Modeling Patterns (One-to-One, One-to-Many, Many-to-Many)
- Schema Validation Rules (MongoDB 3.6+)

---

### 🔹 8. Working with MongoDB in Code
- Connecting using Node.js (`mongoose`, `mongodb`)
- CRUD Operations via code
- Mongoose Basics:
  - Models, Schemas
  - Middleware (Pre/Post Hooks)
  - Validation & Population

---

### 🔹 9. Security & Administration
- User Roles & Authentication
- IP Whitelisting (Atlas)
- Backup & Restore
- Indexing for Security
- Common Admin Commands

---

### 🔹 10. Tools & Ecosystem
- MongoDB Atlas (Cloud)
- MongoDB Compass (GUI)
- Mongoose (ODM)
- Robo 3T / Studio 3T
- Integration with Express.js (MERN stack)

---

## 🧠 SQL (Relational Databases)

### 🔹 1. Introduction to SQL
- What is SQL?
- Popular RDBMS: MySQL, PostgreSQL, SQLite
- Tables, Rows, Columns
- Relational Models & Keys (Primary, Foreign)
- Installing MySQL / PostgreSQL / SQLite

---

### 🔹 2. SQL Basics
- Creating Databases & Tables
- Data Types
- CRUD Operations:
  - `SELECT`, `INSERT`, `UPDATE`, `DELETE`
- WHERE Clauses
- ORDER BY, LIMIT, DISTINCT

---

### 🔹 3. Joins & Relationships
- One-to-One, One-to-Many, Many-to-Many
- INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL JOIN
- SELF JOIN
- ALIASING: `AS`

---

### 🔹 4. Aggregate Functions
- `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`
- `GROUP BY`, `HAVING`

---

### 🔹 5. Subqueries & Nested Queries
- Subqueries in `WHERE`, `SELECT`, `FROM`
- Correlated Subqueries
- `EXISTS`, `IN`, `ANY`, `ALL`

---

### 🔹 6. Constraints & Normalization
- NOT NULL, UNIQUE, DEFAULT
- CHECK, AUTO_INCREMENT
- PRIMARY KEY, FOREIGN KEY
- Normal Forms (1NF, 2NF, 3NF)

---

### 🔹 7. Indexing & Optimization
- Creating & Dropping Indexes
- Composite Indexes
- Query Performance Tips
- `EXPLAIN` Statements

---

### 🔹 8. Views, Transactions & Stored Procedures
- Creating & Using Views
- Transactions: `BEGIN`, `COMMIT`, `ROLLBACK`
- ACID Properties
- Stored Procedures & Functions
- Triggers

---

### 🔹 9. Security & Users
- Creating Users, Granting Permissions
- Password Policies
- SQL Injection Awareness & Prevention
- Backups & Restores

---

### 🔹 10. Tools & Ecosystem
- phpMyAdmin, DBeaver, pgAdmin
- ORM Tools: Sequelize, Prisma, TypeORM, Hibernate
- CLI Tools (`mysql`, `psql`)
- Integration with Node.js / Python / Java

---
