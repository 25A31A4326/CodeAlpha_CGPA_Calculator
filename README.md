# 🎓 CGPA Calculator using C++ (CodeAlpha Internship)

## 📌 Project Title
CGPA Calculator - Academic Performance Analyzer

---

## 🧠 Project Overview
The CGPA Calculator is a C++ console-based application developed to compute a student’s academic performance in terms of GPA and CGPA. It takes multiple course inputs including grades and credit hours, processes them using standard grading logic, and produces accurate results.

This project helps understand how real-world academic grading systems work using programming logic.

---

## 🎯 Objective
- To calculate CGPA based on multiple subjects
- To convert grades into grade points
- To apply weighted average concept using credit hours
- To display structured academic results

---

## ⚙️ Key Concepts Used
- Variables and Data Types
- Conditional Statements (if-else)
- Loops (for loop)
- Arrays / Vectors (STL)
- Arithmetic Operations
- Weighted Average Formula
- Input/Output Streams in C++

---

## 📊 Algorithm / Working Steps

1. Start program
2. Input number of courses (n)
3. For each course:
   - Input Grade (A, B, C, D, F)
   - Input Credit Hours
   - Convert Grade → Grade Points
4. Compute:
   - Total Credits = sum of all credit hours
   - Total Grade Points = sum of (grade points × credits)
5. Calculate CGPA using formula:
   
   CGPA = Total Grade Points / Total Credits

6. Display:
   - Each course details
   - Total credits
   - Final CGPA

---

## 🧮 Grade Point System

| Grade | Grade Point |
|------|------------|
| A    | 10         |
| B    | 8          |
| C    | 6          |
| D    | 4          |
| F    | 0          |

---

## 📐 Formula Used

```text id="cgpa_formula"
CGPA = (Σ Grade Points × Credit Hours) / (Σ Credit Hours)
