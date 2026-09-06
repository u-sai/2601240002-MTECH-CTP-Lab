# Student Attendance Management System

## Overview

The Student Attendance Management System is a Python console application that collects attendance information for multiple students and generates an attendance report.

The program calculates each student's attendance percentage, identifies the student with the highest attendance, and calculates the average attendance percentage of all valid students.

## Features

- Enter the number of students
- Store student details
- Enter total classes conducted
- Enter classes attended
- Validate class information
- Calculate attendance percentage
- Display an attendance report
- Identify the student with the highest attendance
- Calculate average class attendance

## Requirements

- Python 3.x
- No external libraries are required

## How to Run

1. Install Python 3.x.
2. Save the program as `student_attendance.py`.
3. Open a terminal or command prompt.
4. Run:

```bash
python student_attendance.py
```

## Input Details

For each student, the program asks for:

- Student name
- Total classes conducted
- Total classes attended

## Validation

The program checks the entered data.

### Total Classes

Total classes must be greater than zero.

```text
Total classes > 0
```

If the total number of classes is zero or negative, the student data is rejected.

### Attended Classes

The number of attended classes must satisfy:

```text
0 <= Attended Classes <= Total Classes
```

If the value is invalid, the student data is rejected.

## Attendance Calculation

The attendance percentage is calculated using:

```text
Attendance Percentage =
(Classes Attended / Total Classes) × 100
```

### Example

```text
Total Classes = 50
Classes Attended = 45

Attendance =
(45 / 50) × 100

Attendance = 90%
```

## Attendance Analysis

After processing all valid students, the program displays:

- Each student's name
- Total classes
- Classes attended
- Attendance percentage
- Student with the highest attendance
- Average attendance percentage

## Average Attendance Calculation

The program calculates the average of the attendance percentages of all valid students.

```text
Average Attendance =
Sum of All Attendance Percentages / Number of Valid Students
```

## Example Output

```text
========================================
       STUDENT ATTENDANCE REPORT
========================================

Student Name       : Ravi
Total Classes      : 50
Classes Attended   : 45
Attendance %       : 90.00%

Student Name       : Priya
Total Classes      : 50
Classes Attended   : 40
Attendance %       : 80.00%

========================================
         ATTENDANCE ANALYSIS
========================================

Student with Highest Attendance
Name         : Ravi
Attendance % : 90.00%

Average Class Attendance
Average      : 85.00%

========================================
```

## Concepts Used

- Lists
- Dictionaries
- `for` loops
- `if` statements
- User input
- Validation
- Arithmetic operations
- Percentage calculation
- Formatted output
- Finding maximum values
- Calculating averages

## Project Type

**Python Console Application**

## Learning Objective

This project demonstrates how Python can be used to collect, validate, process, and analyze student attendance data.
