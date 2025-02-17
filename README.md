# Pewlett Hackard Employee Database Analysis

## Background
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard, a fictional company. Your first major task is a research project on employees who worked at the company during the 1980s and 1990s. The only available data consists of six CSV files containing historical employee records.

For this project, you will design tables to store the CSV data, import the data into a SQL database, and perform data analysis. This project involves three key areas:

- **Data Modeling**
- **Data Engineering**
- **Data Analysis**

---

## Before You Begin
1. **Create a New Repository**:
   - Name it **sql-challenge**.
   - Do **not** add this project to an existing repository.

2. **Clone the Repository** to your local machine.

3. **Create a Project Directory**:
   - Name the folder according to the challenge, such as **EmployeeSQL**.
   - Add all project-related files to this folder and push your changes to GitHub.

4. **Download the Required Files**
   - Use the provided CSV files to structure and populate your database.

---

## Project Breakdown
### 1. Data Modeling
- Inspect the CSV files and determine table structures.
- Create an **Entity Relationship Diagram (ERD)** using a tool like **QuickDBD**.

### 2. Data Engineering
- **Design a Table Schema**:
  - Define data types.
  - Set **Primary Keys (PKs)**.
  - Establish **Foreign Keys (FKs)**.
  - Identify and create **composite keys** if needed.
  
- **Create SQL Tables in the Correct Order**:
  - Ensure foreign keys reference existing tables.

- **Import CSV Data into SQL Tables**:
  - Load data in the same order as the table creation sequence.
  - Ensure headers are correctly handled during import.

### 3. Data Analysis
Use SQL queries to answer the following questions:

1. Retrieve the **employee number, last name, first name, sex, and salary** of each employee.
2. Retrieve the **first name, last name, and hire date** of employees hired in 1986.
3. Retrieve **department managers** with their department number, department name, employee number, last name, and first name.
4. Retrieve **department numbers and names** for each employee.
5. Retrieve first name, last name, and sex of employees whose **first name is 'Hercules'** and **last name starts with 'B'**.
6. Retrieve all employees in the **Sales department**, including their employee number, last name, and first name.
7. Retrieve all employees in the **Sales and Development departments**, including their employee number, last name, first name, and department name.
8. Retrieve a **count of last names**, in descending order, to see how many employees share each last name.

---
### 4. Sources

- Used QuickDBD for the image as well as ChatGPT/Xpert for specific assistance and questions regarding the assigment.
  



