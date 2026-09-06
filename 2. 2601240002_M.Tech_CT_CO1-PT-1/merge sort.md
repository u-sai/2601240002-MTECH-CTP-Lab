# Student Marks Sorting and Scholarship Eligibility Using Merge Sort

## Introduction

This program is used to store the names and marks of 10 students. The students are sorted according to their marks in descending order using the Merge Sort algorithm.

After sorting the students, the program checks which students are eligible for a scholarship. A student is eligible when their marks are greater than or equal to 90.

## Input

The program contains 10 student names along with their marks.

Example:

* Rahul - 85
* Priya - 92
* Arun - 78
* Sneha - 95
* Kiran - 88
* Divya - 91
* Ravi - 67
* Anjali - 89
* Vijay - 96
* Pooja - 93

## Working

First, the student details are stored in a list.

The Merge Sort algorithm is used to arrange the students based on their marks. The sorting is done in descending order, so the student with the highest marks comes first.

After sorting, the program checks the marks of each student. If the marks are 90 or above, that student is considered eligible for the scholarship.

## Scholarship Criteria

The scholarship eligibility condition is:

```text
Marks >= 90
```

## Output

The program displays all students in descending order of marks and then displays only the students who are eligible for the scholarship.

For the given data, the eligible students are:

```text
Vijay - 96
Sneha - 95
Pooja - 93
Priya - 92
Divya - 91
```

## Algorithm Used

Merge Sort is used for sorting the students.

The time complexity of Merge Sort is:

```text
O(n log n)
```

This makes Merge Sort useful for sorting a large number of student records efficiently.
