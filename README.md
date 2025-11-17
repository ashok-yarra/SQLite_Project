# Car Sales Management Database (SQLite + Python)

This project implements a complete Car Sales Management System using SQLite and Python. The aim is to model real dealership operations such as managing customers, car inventory, sales orders, payments, and test drives. The database follows a clean relational structure with well-defined constraints and realistic synthetic data generated programmatically.

## Project Overview
The database contains six interconnected tables that represent the workflow of a modern car dealership:
- Dealerships
- Customers
- Car Inventory
- Sales Orders
- Payments
- Test Drives

All data was created using Python, ensuring referential integrity and consistent foreign keys.

## Technologies Used
- SQLite
- Python (sqlite3, random, datetime, numpy)
- DB Browser for SQLite for validation

## Key Features
- Six-table normalized relational schema
- Realistic synthetic dataset with over 5,000 total records
- Primary keys, foreign keys, and constraints included
- Nominal, ordinal, interval, and ratio data types represented
- Complete Python notebook with structured cells and comments
- Final row-count validation for accuracy

## Final Table Row Counts
dealerships      -> 15
customers        -> 1500
cars_inventory   -> 600
sales_orders     -> 420
payments         -> 1047
test_drives      -> 1409

## Files Included
- Cars_DataBase.ipynb  (full code)
- car_sales.db         (final SQLite database)
- appendix/            (screenshots from DB Browser)
- README.md            (project documentation)

## Appendix
All validation screenshots are located in the appendix folder.

## Author
Ashok Yarra
MSc Data Science Student
