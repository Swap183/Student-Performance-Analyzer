# 🎓 Student Performance Analyzer

A Python-based project designed to analyze and evaluate student academic performance using **Python, NumPy, Pandas, and Object-Oriented Programming (OOP)** concepts.

This project processes student data, performs statistical analysis, generates insights, and saves reports while handling errors gracefully using exception handling.

---

## 📌 Project Overview

The objective of this project is to help a school analyze the academic performance of students across multiple subjects.  

The program:
- Accepts student details from the user
- Stores and manages data using structured formats
- Performs statistical analysis using NumPy
- Generates reports using Pandas
- Implements OOP for clean architecture
- Handles runtime errors effectively

---

## 🎯 Key Features

### 1️⃣ Data Handling (Python Basics)
- Accepts student details:
  - Name
  - Roll Number
  - Age
  - Class
  - Subject-wise Marks
- Stores data using dictionaries and lists
- Displays formatted student details

---

### 2️⃣ NumPy Analysis
- Stores marks using NumPy arrays
- Calculates:
  - Average marks per student
  - Highest marks per subject
  - Lowest marks per subject
  - Overall class performance:
    - Mean
    - Median
    - Standard Deviation

---

### 3️⃣ Pandas Analysis
- Converts student data into a Pandas DataFrame
- Displays:
  - Top 5 students based on average marks
  - Bottom 5 students based on average marks
- Groups students by class and calculates average marks
- Exports final report to CSV file (`student_report.csv`)

---

### 4️⃣ Object-Oriented Programming (OOP)

#### 🔹 Student Class
- Attributes:
  - name
  - roll_no
  - age
  - class_name
  - marks
- Methods:
  - Display student details
  - Calculate average marks
  - Assign grade (A, B, C, D, F)

#### 🔹 Classroom Class
- Stores multiple student objects
- Add and remove students
- Calculate overall class performance
- Convert data to DataFrame

---

### 5️⃣ Exception Handling

The program handles:
- Invalid user input (e.g., string instead of integer)
- Calculation errors
- File saving errors
- Unexpected runtime errors

This ensures robustness and prevents program crashes.

---

## 🛠 Technologies Used

- Python 3
- NumPy
- Pandas
- Object-Oriented Programming
- Exception Handling

---

## 📊 Output

The program generates:
- Student performance summary
- Subject-wise statistical analysis
- Class performance metrics
- CSV report file (`student_report.csv`)

---

## 🚀 How to Run

1. Install required libraries:
   ```bash
   pip install numpy pandas
