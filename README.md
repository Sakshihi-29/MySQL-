# 📘 SAITM Department 1 Database (dep1)

This repository contains a MySQL database dump for a sample table named **dep1** from the **SAITM** database.
The table stores basic student information including name, roll number, grade, and marks.

---

## 📂 File Included

* **saitm_dep1.sql** — MySQL dump file containing:

  * Table structure
  * Sample data entries
  * MySQL environment setup instructions

---

## 🗄️ Table: `dep1`

The table contains the following columns:

| Column | Type        | Description        |
| ------ | ----------- | ------------------ |
| name   | VARCHAR(30) | Student's name     |
| rollno | INT         | Unique roll number |
| grade  | VARCHAR(10) | Grade obtained     |
| marks  | INT         | Total marks scored |

---

## 📥 Sample Data Included

The SQL file inserts 7 sample rows into the table:

| Name     | Roll No | Grade | Marks |
| -------- | ------- | ----- | ----- |
| bhawna   | 1       | B     | 55    |
| sakshi   | 2       | A     | 96    |
| ishant   | 3       | C     | 22    |
| sameer   | 4       | D     | 12    |
| siddhant | 5       | B     | 55    |
| ananya   | 6       | A     | 70    |
| pappu    | 7       | F     | 2     |

---

## 🛠️ Requirements

* MySQL 8.0+
* A MySQL client (CLI, phpMyAdmin, Workbench, etc.)

---
Author = Sakshi Sharma
