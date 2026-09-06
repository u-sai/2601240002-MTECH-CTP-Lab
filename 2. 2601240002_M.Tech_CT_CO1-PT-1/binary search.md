University Library Book Search Using Binary Search

Introduction:
This program is designed for a university library where a large number of books
are arranged in increasing order. The book numbers start from 1 and continue up
to 10,00,000.

The main purpose of the program is to find a particular book quickly. Since the
books are already arranged in sorted order, Binary Search can be used instead of
checking every book one by one.

Working:
The program first creates the book numbers from 1 to 10,00,000. The user enters
the book number that needs to be searched.

Binary Search checks the middle element of the current search range. If the
middle book number is smaller than the required book, the search continues in
the right half. If it is larger, the search continues in the left half.

This process continues until the required book is found or the search range
becomes empty.

Example:
If the student searches for book number 75000, the program finds it at position
75000 because the book numbers are arranged in the same order as their positions.

Sample Input:
75000

Sample Output:
Book found
Book Number: 75000
Book Position: 75000

Time Complexity:
O(log n)

Conclusion:
Binary Search is suitable for this problem because the books are already sorted.
It reduces the search area by half at every step and is much faster than checking
all the books one by one.
