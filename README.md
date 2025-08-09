# College Result Management System (SQL)

## 📌 Project Overview
This project is a **College Result Management System** built entirely with SQL.  
It allows you to create a database for managing student records, departments, subjects, and their results.  
The project includes:
- **Database Schema** (table creation scripts)
- **Data Insertion** (sample data insertion)
- **Queries** (to fetch and analyze data)

---

## 📂 Project Structure
```
📦 college-result-management
 ┣ 📜 schema.sql      # SQL script for creating tables
 ┣ 📜 data.sql        # SQL script for inserting sample data
 ┣ 📜 queries.sql     # SQL queries for data retrieval and reporting
 ┗ 📜 README.md       # Project documentation
```

---

## 🛠️ How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/college-result-management.git
   cd college-result-management
   ```

2. **Run the schema file to create the database structure**
   ```sql
   SOURCE schema.sql;
   ```

3. **Insert sample data**
   ```sql
   SOURCE data.sql;
   ```

4. **Run queries to fetch reports**
   ```sql
   SOURCE queries.sql;
   ```

---

## 🗄️ Database Schema
The project contains the following main tables:
- **STUDENTS** – Stores student details
- **DEPARTMENTS** – Stores department information
- **SUBJECTS** – Stores subject details
- **RESULTS** – Stores marks and results of students

---

## 📊 Sample Queries
- List all students
- Find top scorer
- Display department-wise student count
- Show subject-wise average marks

---

## 💡 Notes
- All queries are written in **UPPERCASE** for consistency.
- Data contains **sample Indian Maharashtrian names**.
- Each insert statement in `data.sql` inserts **one record at a time**.

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use and modify.

---
