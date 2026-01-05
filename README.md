# Alfido Tech Internship – Task 2

## Implemented Algorithms
- Merge Sort
- Binary Search
- 0/1 Knapsack (Dynamic Programming)

## Features
- Algorithms implemented using C++
- Execution time measured using chrono library
- Time and space complexity analyzed
- User-friendly input and output
- Well-commented source code

## Build Commands (Using g++)

### Merge Sort
g++ mergesort.cpp -o mergesort ./mergesort
### Knapsack
g++ knapsack.cpp -o knapsack ./knapsack
### Binary Search
g++ binarysearch.cpp -o binarysearch ./binarysearch

## Algorithms Overview

### Merge Sort
- Technique: Divide and Conquer
- Time Complexity: O(n log n) (Best, Average, Worst)
- Space Complexity: O(n)

### Binary Search
- Requirement: Sorted array
- Time Complexity:
  - Best Case: O(1)
  - Average & Worst Case: O(log n)
- Space Complexity: O(1) (Iterative)

### Knapsack (0/1)
- Technique: Dynamic Programming
- Time Complexity: O(nW)
- Space Complexity: O(nW)

Where:
- `n` = number of items
- `W` = knapsack capacity

## Environment
- Operating System: Windows 10 / 11
- Compiler: MinGW-w64 (g++)
- Programming Language: C++ (C++11 standard)
