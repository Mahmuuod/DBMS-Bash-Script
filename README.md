# 🗄️ Simple Bash-Based Database Management System (DBMS)

---

## 🚀 Project Overview

Welcome to your very own **lightweight DBMS** built entirely with **Bash scripting**! 🎉

This project helps you learn and experiment with fundamental database concepts using simple files and shell scripts. Create databases, tables, insert and query data — all from your terminal!

---

## 🌟 Key Features

- 📁 **Database Management**
  - Create and delete multiple databases (folders).
  - Easily switch between databases.

- 🗂️ **Table Management**
  - Define tables with columns, data types (`int` or `string`), and primary keys.
  - Drop tables when you don’t need them anymore.

- ✍️ **Data Operations**
  - Insert new records with type checking and uniqueness enforcement.
  - Select and filter data to find exactly what you need.
  - Update and delete records selectively.

- ⚠️ **Robust Validation**
  - No empty or invalid inputs.
  - Prevent special characters that break file format.
  - Enforce primary key uniqueness.

- 🖥️ **User Friendly CLI**
  - Menu-driven interface with clear prompts.
  - Feedback messages guide you every step of the way.

---

## 📂 Project Structure

Each database is a folder inside the main `Database/` directory.  
Tables consist of:

- Data file: Your actual data, stored as colon-separated values (`:`).  
- Metadata file: `.meta<TableName>` stores your table’s schema.

---

## 🛠️ How To Use

1. **Run the Script**

```bash
chmod +x your_dbms_script.sh
./your_dbms_script.sh


## 🎯 Example Workflows

### Creating a Table

```plaintext
Enter your Table Name: employees
Enter the number of columns: 3
Column 1 Name: id
Data Type (int/string): int
Make this column PRIMARY KEY? (Y/N): Y
...

## Inserting Data:
Enter table name: employees
Enter id: 1001
Enter name: Alice
Enter age: 29

## Selecting Data:

Enter table name: employees
Select a column to filter or press enter to get all rows: name
Enter value to filter by: Alice
