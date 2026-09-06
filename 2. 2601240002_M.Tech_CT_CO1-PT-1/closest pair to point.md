# Closest Pair of ATM Locations

## Introduction

This program is used to find the two closest ATM locations in a city. Each ATM location is represented using an x-coordinate and a y-coordinate.

The program calculates the distance between every pair of ATM locations and finds the pair having the smallest distance.

## Input

The program uses 10 ATM locations with their coordinates.

Example:

* ATM1 - (2, 3)
* ATM2 - (8, 7)
* ATM3 - (4, 6)
* ATM4 - (12, 10)
* ATM5 - (5, 5)
* ATM6 - (9, 8)
* ATM7 - (15, 14)
* ATM8 - (3, 4)
* ATM9 - (11, 9)
* ATM10 - (20, 18)

## Working

First, the ATM names and their coordinates are stored in a list.

The program compares every pair of points. For each pair, it calculates the distance between them using the distance formula.

The distance formula is:

```text
Distance = √((x2 - x1)² + (y2 - y1)²)
```

The program keeps track of the smallest distance found. After checking all the pairs, the two ATM locations having the smallest distance are displayed.

## Output

For the given coordinates, the closest pair is:

```text
ATM1 and ATM8
```

Their coordinates are:

```text
ATM1 = (2, 3)
ATM8 = (3, 4)
```

The distance between them is approximately:

```text
1.41
```

## Algorithm Used

The program uses the Closest Pair of Points approach to find the minimum distance between two points.

For this simple implementation, every possible pair of points is checked.

The time complexity of this approach is:

```text
O(n²)
```

For a small number of points, this method is easy to understand and implement. For a very large number of points, a divide-and-conquer approach can be used to improve the time complexity to:

```text
O(n log n)
```
