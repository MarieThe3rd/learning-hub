# 🗄️ SQL

Master SQL queries, relational database design, stored procedures, and query optimisation.

## 🎯 Learning Goals

- [ ] Write confident SELECT queries including JOINs, GROUP BY, and subqueries
- [ ] Use CTEs and window functions for advanced data analysis
- [ ] Design normalised relational database schemas (1NF–3NF)
- [ ] Understand and use indexes to optimise query performance
- [ ] Write stored procedures, views, and user-defined functions
- [ ] Understand transactions, ACID properties, and isolation levels
- [ ] Read and interpret execution plans
- [ ] Connect SQL knowledge to Entity Framework Core usage in .NET

## 🗺️ Learning Path

### Stage 1: SQL Fundamentals
- SELECT, WHERE, ORDER BY, LIMIT/TOP
- INNER JOIN, LEFT/RIGHT JOIN, FULL OUTER JOIN
- Aggregate functions: COUNT, SUM, AVG, MIN, MAX
- GROUP BY and HAVING

### Stage 2: Intermediate Queries
- Subqueries (correlated and non-correlated)
- Common Table Expressions (CTEs)
- Window functions: ROW_NUMBER, RANK, LEAD, LAG, SUM OVER
- CASE expressions and conditional logic

### Stage 3: Database Design
- Normalisation: 1NF, 2NF, 3NF
- Entity-Relationship Diagrams (ERDs)
- Primary keys, foreign keys, and referential integrity
- Constraints: UNIQUE, NOT NULL, CHECK, DEFAULT

### Stage 4: Stored Procedures & Programmability
- Creating and executing stored procedures
- Parameters, output parameters, and return values
- Views and indexed views
- User-defined functions (scalar and table-valued)
- Triggers (use sparingly)

### Stage 5: Performance & Optimisation
- How indexes work (clustered vs. non-clustered)
- Reading execution plans
- Index strategies: covering indexes, composite indexes
- Identifying and fixing slow queries
- Transaction management and locking

## 📁 Folder Structure

```
topics/sql/
├── notes/       ← Add your markdown notes here
├── exercises/   ← SQL scripts and practice queries
└── README.md    ← This file
```

## 🔗 Related Topics

- **.NET Development** — Entity Framework Core generates SQL from LINQ queries
- **Azure Development** — Azure SQL Database and Cosmos DB
- **Architecture** — Database design decisions and CQRS patterns

## 🤖 Mentor

Use the `@sql-mentor` prompt for SQL-specific guidance, or `@mentor` with `topic = "SQL"`.
