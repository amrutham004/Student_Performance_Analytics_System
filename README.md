

# 🎓 Student Performance Analytics System

**A Python data analysis project that turns raw student records into grades, pass/fail results, subject-wise insights, and visual reports.**


---

## 📑 Table of Contents

- [Overview](#-overview)
- [Objectives](#-objectives)
- [Tech Stack](#-tech-stack)
- [Dataset](#-dataset)
- [Features](#-features)
- [Grading and Pass/Fail Criteria](#-grading-and-passfail-criteria)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Sample Outputs](#-sample-outputs)
- [Challenges and Learning Outcomes](#-challenges-and-learning-outcomes)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 📖 Overview

The **Student Performance Analytics System** processes a dataset of **20 student records** containing subject marks and attendance information. Using **Pandas, NumPy, and Matplotlib**, it calculates total and average marks, assigns grades, classifies students as pass or fail, analyzes performance by subject, identifies top performers, and presents the results through clear charts.

This project was developed as part of the **Python with AI** course.

## 🎯 Objectives

- Load and organize student records using Pandas.
- Calculate total and average marks for each student.
- Assign grades based on predefined grading criteria.
- Identify students who pass or fail.
- Compute overall class performance statistics.
- Perform subject-wise performance analysis.
- Identify the top five performing students.
- Visualize results with Matplotlib charts.

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **Python** | Program logic, functions, loops, and conditions |
| **Pandas** | Dataset loading, processing, sorting, and analysis |
| **NumPy** | Numerical calculations and statistical analysis |
| **Matplotlib** | Data visualization and charts |
| **Microsoft Excel** | Preparing the student dataset |
| **Google Colab** | Writing and executing Python code |
| **GitHub** | Project hosting and version control |

## 🗂 Dataset

The dataset contains **20 student records**, prepared in Microsoft Excel and saved as a CSV file for processing in Python.

| Column | Description |
|---|---|
| `Student ID` | Unique student identifier |
| `Name` | Student name |
| `Department` | Student's academic branch |
| `Mathematics` | Mathematics marks |
| `Python Programming` | Python Programming marks |
| `Engineering Drawing` | Engineering Drawing marks |
| `Attendance Percentage` | Student's attendance percentage |

## ✨ Features

### 1. Dataset Loading and Inspection
- Reads student records from a CSV file using Pandas.
- Displays the dataset and its first five records.
- Examines column names, dimensions, and data types.

### 2. Student Performance Calculation
- Calculates total marks across the three subjects.
- Calculates the average marks for each student.

### 3. Grade Assignment
- Assigns a grade to each student based on average marks (see [grading criteria](#-grading-and-passfail-criteria)).

### 4. Pass/Fail Classification
- Classifies each student as **Pass** or **Fail** using a minimum mark requirement in every subject.

### 5. Overall Performance Analysis
- Total number of students
- Number of students who passed
- Number of students who failed
- Overall class average
- Highest student average
- Lowest student average

### 6. Subject-Wise Analysis
For each subject, the system calculates:
- Average marks
- Highest marks
- Lowest marks
- Number of students who passed
- Number of students who failed

### 7. Data Visualization
Three Matplotlib charts are generated:

| Chart | Type | Description |
|---|---|---|
| Subject-wise average marks | Bar chart | Compares average marks across subjects |
| Pass/fail distribution | Pie chart | Shows the share of passing and failing students |
| Top five performers | Bar chart | Compares the average marks of the five highest-performing students |

### 8. Top Performers
Students are sorted by average marks in descending order, and the top five are listed with their **Student ID, Name, Department, Average Marks, and Grade**.

## 📏 Grading and Pass/Fail Criteria

**Grades** are assigned according to each student's average marks:

| Average Marks | Grade |
|:---:|:---:|
| 90 – 100 | **A+** |
| 80 – 89.99 | **A** |
| 70 – 79.99 | **B+** |
| 60 – 69.99 | **B** |
| 50 – 59.99 | **C** |
| Below 50 | **F** |

**Result:** A student **passes** only if they score **at least 40 marks in every subject**. Scoring below 40 in any one subject results in **Fail**.

## 📁 Project Structure

```text
Student_Performance_Analytics_System/
├── main.py                    # Main analysis and visualization script
├── students.csv               # Student dataset
├── requirements.txt           # Python dependencies
├── Project_Documentation.pdf  # Detailed project documentation
└── README.md                  # Project overview
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x
- Google Colab **or** a local Python environment
- Internet access to install the required libraries

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/amrutham004/Student_Performance_Analytics_System.git
   cd Student_Performance_Analytics_System
   ```

2. **Install the dependencies**

   ```bash
   pip install pandas numpy matplotlib
   ```

### Usage

1. Make sure `students.csv` is in the same directory as `main.py`.
2. Run the program:

   ```bash
   python main.py
   ```

> **Using Google Colab?** Upload the dataset to your Colab session and run the notebook cells instead.

## 📊 Sample Outputs

### 1. Dataset Loaded in Python
<img width="859" height="953" alt="Dataset loaded in Python" src="https://github.com/user-attachments/assets/16ec2311-3267-4d05-8f17-5367b981b65d" />

### 2. First Five Records
<img width="759" height="328" alt="First five records" src="https://github.com/user-attachments/assets/f342eddd-fa20-47e8-91b1-4edf2153ce7d" />

### 3. Dataset Information
<img width="891" height="376" alt="Dataset information" src="https://github.com/user-attachments/assets/2f4928ba-105e-49ad-b462-27bd48588395" />

### 4. Total Marks and Average Marks of Each Student
<img width="536" height="896" alt="Total and average marks of each student" src="https://github.com/user-attachments/assets/79fbb431-ffd1-4687-bf49-119923f79e5c" />

### 5. Grades Calculation
<img width="334" height="470" alt="Grades calculation" src="https://github.com/user-attachments/assets/5ffec48d-1e1a-4fc2-aef8-8e4c1521c01d" />

### 6. Pass/Fail Distribution
<img width="721" height="469" alt="Pass/fail distribution" src="https://github.com/user-attachments/assets/3770d4d5-d7bf-4759-a4a2-d1e8dc05fe0f" />

### 7. Student Performance
<img width="734" height="513" alt="Student performance" src="https://github.com/user-attachments/assets/7191a98a-e909-4354-ac17-2a787d137550" />

### 8. Overall Performance
<img width="658" height="169" alt="Overall performance summary" src="https://github.com/user-attachments/assets/32d86d2b-7ae6-4445-b76f-3acc5923db38" />

### 9. Subject-Wise Performance Analysis
<img width="858" height="501" alt="Subject-wise performance analysis" src="https://github.com/user-attachments/assets/61c2b486-1db3-4559-b56a-03eeb752341a" />

### 10. Data Visualization

**Subject-wise average marks (bar chart)**

<img width="472" height="293" alt="Subject-wise average marks bar chart" src="https://github.com/user-attachments/assets/0470604c-0c32-4cc1-9b18-5e8efde9e73a" />

**Pass/fail distribution (pie chart)**

<img width="420" height="437" alt="Pass/fail distribution pie chart" src="https://github.com/user-attachments/assets/6d2e6842-6c08-401f-8d87-6809322628f6" />

**Top five performers (bar chart)**

<img width="940" height="658" alt="Top five performers bar chart" src="https://github.com/user-attachments/assets/03168c6c-ee10-4a51-9edc-e8e450453b92" />

## 💡 Challenges and Learning Outcomes

- Loaded and processed CSV data using **Pandas**.
- Practiced Python fundamentals: variables, data types, loops, conditional statements, and functions.
- Applied **NumPy** for numerical calculations and statistical analysis.
- Created charts with **Matplotlib** to communicate results visually.
- Resolved column-name errors when reading the CSV file by cleaning headers with `strip()` to remove stray whitespace.
- Gained hands-on experience analyzing a student dataset and presenting meaningful results.


## 👩‍💻 Author

**Amrutha M**
Python with AI, Student Performance Analytics System


⭐ If you found this project helpful, consider giving it a star!
