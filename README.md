# college-admissions-sql
🎯 Problem Statement

Design and implement a structured relational database system that models a real-world scenario, ensuring:

Proper table relationships

Elimination of redundancy (Normalization)

Enforcement of data integrity using constraints

Efficient querying for analytical insights

The system must support data storage, retrieval, filtering, aggregation, and reporting.

🛠 Tech Stack

Database Engine: SQLite

Language: SQL

Environment: SQLite CLI / DB Browser for SQLite

🗂 Project Structure
Project-DB-SQL/
│
├── College_admissions.db       # SQLite database file
├── codes_tables.sql            # Schema creation & table definitions
├── Project_queries.sql         # All query implementations
└── README.md
🧱 Database Design

The database includes:

Multiple related tables

Primary Keys & Foreign Keys

Constraints (NOT NULL, UNIQUE, etc.)

Proper normalization structure

Referential integrity

The schema supports realistic entity relationships and structured data flow.

🔎 SQL Concepts Implemented

This project includes implementation of:

Basic SELECT queries

WHERE filtering

ORDER BY

INNER JOIN / LEFT JOIN

GROUP BY with Aggregations

Subqueries

Nested queries

Data constraints

Relational mapping

This ensures coverage of both foundational and advanced SQL concepts.

📊 Data

The database uses dummy data to simulate real-world scenarios and enable query testing.

Even though the dataset is simulated, it reflects realistic structure and logical relationships between entities.

🚀 How to Run
Option 1 – Using SQLite CLI
sqlite3 College_admissions.db
.read codes_tables.sql
.read Project_queries.sql
Option 2 – Using DB Browser

Open DB Browser for SQLite

Load College_admissions.db

Execute queries from Project_queries.sql

👥 Team Members

Varshan R K

Rashika S

Mohith B N

📈 Learning Outcomes

Through this project, we developed:

Strong understanding of relational database design

Practical implementation of normalization

Experience handling structured query logic

Analytical thinking using SQL

Team collaboration in database development

🔮 Future Improvements

Integrating the database with a frontend interface

Adding triggers and indexing for performance optimization

Converting into a web-based application

Connecting to data visualization tools

📄 License

This project was developed for academic purposes.
