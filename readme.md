

### 1️⃣ What is PostgreSQL?

PostgreSQL is an open-source, object-relational database management system (ORDBMS). It supports SQL standards and advanced features like transactions, indexing, stored procedures, and extensibility. It is known for its reliability, scalability, and strong community support, making it widely used in enterprise applications.

---

### 2️⃣ What is the purpose of a database schema in PostgreSQL?

A schema in PostgreSQL is a logical structure that organizes database objects such as tables, views, and functions. It acts as a namespace to prevent naming conflicts and allows multiple users or applications to work within the same database using isolated object sets.

---

### 3️⃣ Explain the Primary Key and Foreign Key concepts in PostgreSQL.

- **Primary Key**: A column or group of columns that uniquely identifies each row in a table. It must be unique and not null.
- **Foreign Key**: A column that references a primary key in another table, establishing a relationship between the two tables and ensuring referential integrity.

---

### 4️⃣ What is the difference between the `VARCHAR` and `CHAR` data types?

- **CHAR(n)**: A fixed-length character type. It always stores `n` characters, padding with spaces if necessary.
- **VARCHAR(n)**: A variable-length character type. It stores up to `n` characters without padding, making it more space-efficient.
`VARCHAR` is generally preferred unless a fixed size is required.

---

### 5️⃣ Explain the purpose of the `WHERE` clause in a `SELECT` statement.

The `WHERE` clause filters records returned by a `SELECT` query based on a specified condition. Only rows that meet the condition are returned.

Example:
```sql
SELECT * FROM employees WHERE department = 'HR';
