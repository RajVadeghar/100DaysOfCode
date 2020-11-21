# 100DaysOfCode
> Trying to implement *data structures* and *algorithms* in this project. Everthing here in this project is **C++**

# ***ARRAYS***
### Day 1
> [C++ program to reverse an array](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-1/reverseArray.cpp)
```
Example 1:
Input   : array[] = {1, 2, 3}
Output  : array[] = {3, 2, 1}

Example 2:
Input   :  array[] = {4, 5, 1, 2}
Output  : array[] = {2, 1, 5, 4}
```

### Day 2
> [C++ program to sort array using MERGE SORT](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-2/mergesort.cpp)
```
Example:
Input   : array[] = {4, 5, 1, 7}
Output  : array[] = {1, 4, 5, 7}
```
### Day 3
> [C++ program to find the minimum and maximum elements in an array.](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-3/minMax.cpp)
```
Example:
Input   : array[] = {4, 5, 10, 25, 2, 3}
Ouput   : min = 2, max = 25
```
> [C++ program to find the kth smallest element in an array.](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-3/kthSmallest.cpp)
```
Example:
Input   : array[] = {7, 10, 4, 3, 20, 15}, k = 2
Output  : 7
Explanation : k is 2, so 2nd smallest element is 7
```
### Day 4
> [C++ program to sort the array of 0s, 1s, 2s in ascending order without using any sorting algorithm.](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-4/sorting.cpp) <br />
> Given an array containing 0s, 1s, and 2s; you need to sort the array in ascending order.
```
Example:
Input   : array[] = {2, 1, 1, 0, 0, 2, 0, 1}
Output  : array[] = {0, 0, 0, 1, 1, 1, 2, 2}
```
### Day 5
> [C++ program to move all the negative numbers to the beginning of the array.](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-5/rearrange.cpp) <br />
> An array contains both positive and negative numbers in random order.Rearrange the array elements so that all negative numbers appear before all positive numbers.
```
Example:
Input   : array[] = {1, -5, -6, 10, 25, 33, -20}
Output  : array[] = {-20, -5, -6, 10, 25, 33, 1}

Note : Order of elements is not important here. 
```
### Day 6
> [C++ program to find union count of two arrays](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-6/union.cpp)
```
Example:
Input   : array[] = {1, 2, 3, 4, 5}, array[] = {1, 2, 7}
Output  : 6
```

### Day 7
> [C++ program to rotate an array by one element each](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-7/rotate.cpp)
```
Example:
Input   : array[] = {1, 2, 3, 4, 5}
Output  : array[] = {5, 1, 2, 3, 4}
```

### Day 8
> [C++ program to minimize the maximum difference between the heights](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-8/diff.cpp)<br />

> Given an array arr[] denoting heights of N towers and a positive integer K. You have to modify the height of each tower either by increasing or decreasing them by K only once. After modifying, height should be a non-negative integer. Find out what could be the possible minimum difference of the height of shortest and longest towers after.
```
Example 1:
Input: K = 2, N = 4, Arr[] = {1, 5, 8, 10}
Output: 5
Explanation: The array can be modified as {3, 3, 6, 8}.
The difference between the largest and the smallest is 8-3 = 5.

Example 2:
Input: K = 3, N = 5, Arr[] = {3, 9, 12, 16, 20}
Output: 11
Explanation: The array can be modified as {6, 12, 9, 13, 17}.
The difference between the largest and the smallest is 17-6 = 11.
```

### Day 9
> [C++ program to find minimum number of jumps reqired to reach end of array](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-9/NoOfJumps.cpp)
```
Example-1:
Input   : array[] = {1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9}
Output  : 3

Example-2:
Input   : array[] = {1, 4, 3, 2, 6, 7}
Output  : 2
```

### Day 10
> [C++ program to find duplicates in an array](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-10/duplicate.cpp)<br />

> Given an array of size n + 1, which contains n distinct elements and 1 element is repeated. The task is to find out the repeated element.
```
Example-1:
Input   : array[] = {1, 3, 4, 2, 2}
Output  : 2

Example-2:
Input   : array[] = {3, 1, 3, 4, 2}
Output  : 3

Example-3:
Input   : array[] = {1, 1}
Output  : 1
```

### Day 11
> [C++ program to merge two sorted arrays without using extra space](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-11/merge.cpp)<br />

> Given two sorted arrays arr1[], arr2[] of size1, size2. Each array is sorted in non-decreasing order. Merge the two arrays into one sorted array in non-decreasing order without using any extra space.

```
Example 1:

Input:
        size1 = 4, size2 = 5
        arr1[] = {1, 3, 5, 7}
        arr2[] = {0, 2, 6, 8, 9}

Output: 0 1 2 3 5 6 7 8 9

Explanation: Since you can't use any extra space, modify the given arrays to form 
        arr1[] = {0, 1, 2, 3}
        arr2[] = {5, 6, 7, 8, 9}

Example 2:

Input:
        size1 = 2, size2 = 3
        arr1[] = {10, 12}
        arr2[] = {5, 18, 20}

Output: 5 10 12 18 20

Explanation: Since you can't use any extra space, modify the given arrays to form 
        arr1[] = {5, 10}
        arr2[] = {12, 18, 20}
```

### Day 12
> [C++ program to find largest sum contiguous sub array](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-12/kadanes.cpp)<br />

> Given an array array of N integers. Find the contiguous sub-array with maximum sum.

```
Example 1:

Input: 
        N = 5
        arr[] = {1,2,3,-2,5}
Output: 9

Explanation: Max subarray sum is 9 of elements (1, 2, 3, -2, 5) which is a contiguous subarray.

Example 2:

Input:
        N = 4
        arr[] = {-1,-2,-3,-4}
Output: -1

Explanation: Max subarray sum is -1 of element (-1)
```

### Day 13
> [C++ program to merge the overlapping intervals](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-13/mergeIntervals.cpp)<br />

> Given an array of intervals where intervals[i] = [starti, endi], merge all overlapping intervals, and return an array of the non-overlapping intervals that cover all the intervals in the input.

```
Example 1:

Input: intervals = [[1,3],[2,6],[8,10],[15,18]]
Output: [[1,6],[8,10],[15,18]]
Explanation: Since intervals [1,3] and [2,6] overlaps, merge them into [1,6].

Example 2:

Input: intervals = [[1,4],[4,5]]
Output: [[1,5]]
Explanation: Intervals [1,4] and [4,5] are considered overlapping.
```

### Day 14
> [C++ program to find best time to buy and sell stock](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-14/buyAndSellStock.cpp)<br />

> Say you have an array for which the ith element is the price of a given stock on day i. If you were only permitted to complete at most one transaction (i.e., buy one and sell one share of the stock), design an algorithm to find the maximum profit. Note that you cannot sell a stock before you buy one.

```
Example 1:

        Input: [7,1,5,3,6,4]
        Output: 5
        Explanation: Buy on day 2 (price = 1) and sell on day 5 (price = 6), profit = 6-1 = 5.
                        Not 7-1 = 6, as selling price needs to be larger than buying price.
Example 2:

        Input: [7,6,4,3,1]
        Output: 0
        Explanation: In this case, no transaction is done, i.e. max profit = 0.
```

### Day 15
> [C++ program to find common elements of given 3 arrays by user](https://github.com/RajVadeghar/100DaysOfCode/blob/main/Day-15/commonOf3Arrays.cpp)<br />

> Given three arrays sorted in increasing order. Find the elements that are common in all three arrays.

> **Note**: can you take care of the duplicates without using any additional Data Structure?

```
Example:

Input:
        n1 = 6; A = {1, 5, 10, 20, 40, 80}
        n2 = 5; B = {6, 7, 20, 80, 100}
        n3 = 8; C = {3, 4, 15, 20, 30, 70, 80, 120}
Output: 20 80
Explanation: 20 and 80 are the only common elements in A, B and C.
```
