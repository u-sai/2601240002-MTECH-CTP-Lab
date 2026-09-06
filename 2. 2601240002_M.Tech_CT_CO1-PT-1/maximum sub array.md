Maximum Subarray Algorithm Using Daily Shop Profit and Loss
Introduction

This program is used to find the continuous period that gives the maximum total profit for a shop.

The shop records its daily profit or loss for several days. Some days may have a profit and some days may have a loss.

The program finds the continuous group of days having the maximum total profit.

Input

The program uses the following daily profit and loss values:

10, -5, 20, -10, 30, -15, 5, -2, 8, -20

Positive values represent profit and negative values represent loss.

Working

The program goes through the list from left to right.

It keeps two values. One value stores the current subarray sum and the other stores the maximum sum found so far.

For every value, the program checks whether it is better to start a new subarray or continue with the current subarray.

When a larger sum is found, the program stores its starting and ending positions.

At the end, the program displays the maximum profit and the days that produce that profit.

Output

The maximum profit is:

45

The days included in the maximum subarray are:

Day 1 : 10
Day 2 : -5
Day 3 : 20
Day 4 : -10
Day 5 : 30

The total is:

10 - 5 + 20 - 10 + 30 = 45
Algorithm Used

The program uses the Maximum Subarray Algorithm, commonly implemented using Kadane's Algorithm.

The main idea is to keep track of the current sum and the maximum sum obtained so far.

The time complexity of the algorithm is:

O(n)

The algorithm only needs to go through the list once, so it is efficient for finding the maximum sum of a continuous subarray.
