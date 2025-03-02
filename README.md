# Dynamic SQL Sequence-Trigger Generator for Oracle

## 📌 Overview
This script automates the creation of **sequences and triggers** for tables with **single-column numeric primary keys** in an **Oracle database**. It ensures that new records automatically receive a unique primary key by linking a sequence to each table.

## ✨ Features
✔ **Drops existing sequences** to prevent duplication.  
✔ **Identifies tables** with single-column numeric primary keys.  
✔ **Creates sequences** starting from `MAX(primary key) + 1`.  
✔ **Generates triggers** to auto-assign sequence values before inserts.  

## 🛠️ Technologies Used
- **Oracle SQL** – Dynamic SQL execution for sequence & trigger management.  
- **PL/SQL Cursors** – Iterates through existing tables & sequences.  

## 🚀 How It Works
1. **Drops existing sequences** from the database.
2. **Finds tables** with a single numeric primary key.
3. **Creates a sequence** for each table starting from the max primary key value.
4. **Generates a trigger** to auto-assign primary key values on insert.



