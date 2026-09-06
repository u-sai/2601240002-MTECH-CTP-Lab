# Employee Salary Sorting Using Quick Sort

## Introduction

This program is used to store the names and salaries of 10 employees. The employees are sorted according to their salary in descending order using the Quick Sort algorithm.

After sorting the employees, the program checks which employees are eligible for a salary benefit. Employees having a salary of 50,000 or more are considered eligible.

## Input

The program contains 10 employees with their salaries.

Example:

* Ramesh - 45000
* Anitha - 62000
* Karthik - 38000
* Deepa - 75000
* Sanjay - 52000
* Pavan - 48000
* Neha - 68000
* Rohit - 41000
* Swathi - 58000
* Ajay - 83000

## Working

First, the employee names and salaries are stored in a list.

Quick Sort is used to arrange the employees based on their salaries. The salaries are arranged in descending order, so the employee with the highest salary comes first.

The program selects a pivot and compares the other salaries with the pivot. The employees are then divided into different parts and the same process is repeated until the complete list is sorted.

After sorting, the program checks the salary of each employee.

If the salary is greater than or equal to 50,000, the employee is displayed as eligible for the salary benefit.

## Eligibility Criteria

The condition used in this program is:

```text
Salary >= 50000
```

## Output

The employees are displayed from the highest salary to the lowest salary.

The employees eligible for the benefit are:

```text
Ajay - 83000
Deepa - 75000
Neha - 68000
Anitha - 62000
Swathi - 58000
Sanjay - 52000
```

## Algorithm Used

The Quick Sort algorithm is used to sort the employee salaries.

The average time complexity of Quick Sort is:

```text
O(n log n)
```

The worst-case time complexity is:

```text
O(n²)
```

Quick Sort is an efficient sorting algorithm and is useful when a large amount of data needs to be sorted.
