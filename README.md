# Business Analytics Assignments - Complete Multi-Part Project

## Overview

This comprehensive business analytics assignment covers the complete data journey from raw data cleaning through to enterprise architecture design. The project demonstrates proficiency in multiple database paradigms, data warehousing, vector databases, data lakes, and system architecture design.

### 📚 Project Structure

```
Business-Analytics-Assignments/
├── part1_grade_tracker.py           # Part 1: Python Basics & Control Flow
├── part1-rdbms/                     # Part 1: RDBMS concepts
├── part2-nosql/                     # Part 2: NoSQL & MongoDB
├── part3-datawarehouse/             # Part 3: Data Warehouse & Star Schema
├── part4-vector-db/                 # Part 4: Vector Databases & Embeddings
├── part5-datalake/                  # Part 5: Data Lake Architecture
└── part6-capstone/                  # Part 6: Capstone - Healthcare System Design
```

---

## Part 1: Python Basics & Control Flow - Student Grade Tracker

### 📖 Description
A command-line application that manages student data, performs data cleaning, computes results, and generates comprehensive summary reports using fundamental Python concepts.

### 🎯 Tasks Covered

**Task 1: Data Parsing & Profile Cleaning (5 marks)**
- ✅ Parse raw student data with inconsistent formatting
- ✅ Clean and normalize names (remove whitespace, apply Title Case)
- ✅ Convert roll numbers from strings to integers
- ✅ Parse marks as comma-separated strings and convert to integer lists
- ✅ Validate names (alphabetic characters only)
- ✅ Print formatted profile cards using f-strings

**Task 2: Compute Results & Statistics (10 marks)**
- ✅ Calculate total marks per student
- ✅ Compute average scores
- ✅ Assign grades based on performance (A+, A, B, C, D, F)
- ✅ Rank students by total marks
- ✅ Generate class-level statistics

**Task 3: Generate Summary Report (10 marks)**
- ✅ Individual student report cards with visual formatting
- ✅ Class summary with overall metrics
- ✅ Rank-wise student listing
- ✅ Subject-wise performance statistics

**Additional Features (Bonus):**
- ✅ Special string operations (uppercase, lowercase, swapcase)
- ✅ Subject-wise statistical analysis
- ✅ Passing/failing student counts
- ✅ Highest and lowest scorer identification
- ✅ Modular function design for reusability

### 🚀 Usage

```bash
# Navigate to the assignment directory
cd Business-Analytics-Assignments

# Run the grade tracker
python part1_grade_tracker.py
```

### 📊 Output Features

- **Data Validation**: Shows validation status for each student record
- **Formatted Cards**: Individual profile cards for each student
- **Class Summary**: Comprehensive statistics including class average, pass/fail rates
- **Ranking System**: Students ranked by total performance
- **Special Operations**: Demonstrates string manipulation (UPPERCASE, lowercase)
- **Subject Analysis**: Average, min, and max scores per subject

---

## Part 1-Extended: RDBMS Fundamentals

### 📁 Files in `part1-rdbms/`

- **schema_design.sql**: Relational schema for a sales management system
  - 4 tables: customers, products, salesrep, orders
  - Primary and foreign key relationships
  
- **queries.sql**: Complex SQL queries demonstrating:
  - JOINs across multiple tables
  - Aggregation functions (SUM, AVG, COUNT, MAX)
  - GROUP BY and ORDER BY clauses
  - Business intelligence queries

- **normalization.md**: Database normalization concepts
  - Identification of anomalies (Insert, Update, Delete)
  - Normalization to 3NF
  - Real-world examples

---

## Part 2: NoSQL & MongoDB

### 📁 Files in `part2-nosql/`

- **mongo_queries.js**: MongoDB operations
  - Document insertion with nested structures
  - Query examples on semi-structured data
  
- **sample_documents.json**: Sample product documents
  - Electronics (products with detailed specifications)
  - Clothing (items with variants)
  - Nested object structure examples

- **rdbms_vs_nosql.md**: Comparative analysis
  - ACID vs BASE properties
  - CAP theorem discussion
  - Use case recommendations (healthcare system example)

---

## Part 3: Data Warehouse & Star Schema

### 📁 Files in `part3-datawarehouse/`

- **star_schema.sql**: Star schema design
  - Central fact table (fact_sales)
  - 4 dimension tables (store, product, customer, date)
  - Optimized for OLAP queries

- **dw_queries.sql**: Analytical queries
  - Revenue analysis by category and time
  - Top performers identification
  - Trend analysis

- **etl_notes.md**: ETL process documentation
  - Data format standardization
  - Category normalization
  - Handling missing values

---

## Part 4: Vector Databases & Embeddings

### 📁 Files in `part4-vector-db/`

- **embeddings_demo.ipynb**: Jupyter notebook demonstrating
  - Sentence embeddings using SentenceTransformer
  - Semantic similarity computation
  - Cosine similarity calculations

- **vector_db_reflection.md**: Conceptual analysis
  - Limitations of lexical search
  - Advantages of semantic search
  - Vector database applications

---

## Part 5: Data Lake Architecture

### 📁 Files in `part5-datalake/`

- **duckdb_queries.sql**: Multi-format queries
  - CSV data ingestion
  - JSON data processing
  - Parquet file analytics

- **architecture_choice.md**: Architecture justification
  - Datalakehouse benefits
  - Cost-effectiveness analysis
  - Query and ML capabilities

---

## Part 6: Capstone Project - Healthcare System Architecture

### 📁 Files in `part6-capstone/`

- **design_justification.md**: Complete architecture design
  - MySQL for OLTP (patient data)
  - Cassandra for time-series (IoT sensor data)
  - Data lake for raw data ingestion
  - Snowflake for analytical workloads
  - Hybrid real-time/batch processing

- **architecture_diagram.png**: Visual system design

---

## 🛠️ Technical Stack

- **Language**: Python 3.14+
- **Databases**: 
  - SQL: MySQL, DuckDB
  - NoSQL: MongoDB
  - Specialized: Cassandra, Snowflake
  - Vector: Vector AI databases
- **Tools**: Jupyter Notebooks, Git
- **Concepts**: ETL, Data warehouse, Star schema, Vector embeddings

---

## 📋 Key Learning Outcomes

1. **Python Fundamentals**: Data parsing, string manipulation, control flow
2. **Relational Databases**: Schema design, normalization, complex queries
3. **NoSQL Paradigm**: Document databases, semi-structured data
4. **Data Warehousing**: Dimensional modeling, analytical queries, ETL
5. **Emerging Tech**: Vector databases, semantic search
6. **System Design**: Multi-technology architecture, trade-off analysis
7. **Professional Skills**: Code documentation, modular design, reporting

---

## 💾 How to Submit

1. **Push to GitHub**: All files are in a public GitHub repository
2. **Include Comments**: Code includes extensive documentation
3. **Test Everything**: All scripts are tested and validated
4. **Document Design**: Each architectural choice is justified

---

## 📞 Support & Questions

For each section, refer to the dedicated README or documentation files:
- Parts 1-3: Query-focused, refer to SQL files
- Part 4: Jupyter notebook for hands-on exploration
- Part 5-6: Architecture decisions documented in markdown files

---

**Status**: ✅ Complete and Ready for Submission
**Last Updated**: 2024
**Version**: 1.0