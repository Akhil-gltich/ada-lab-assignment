# ADA Lab Assignment 1 – Algorithm Foundations

## Student Information
Name: Akhil Singh  
Roll No.: 2401010148  
Section: C  
Program: B.Tech CSE  
Course: Analysis and Design of Algorithms Lab  

---

# Assignment Overview
This assignment focuses on understanding algorithm efficiency through time complexity analysis, recurrence relations, recursion, and search algorithms. The goal is to observe how algorithms behave with increasing input sizes and compare their performance.

---

# Tasks Implemented

## Task 1: Algorithm Growth Observation
Implemented algorithms with different time complexities:

- O(1) – Constant Time
- O(n) – Linear Time
- O(n²) – Quadratic Time
- O(log n) – Logarithmic Time

Execution time was measured for input sizes:
n = 10, 100, 500, 1000


A graph was generated to visualize how execution time increases with input size.

### Observation
- O(1) remains constant.
- O(log n) grows very slowly.
- O(n) grows linearly.
- O(n²) increases very rapidly as input grows.

---

# Task 2: Best, Average, and Worst Case Analysis

Implemented:

- Linear Search
- Binary Search

Execution time was measured for different array sizes.

### Comparison

| Algorithm | Best Case | Average Case | Worst Case |
|-----------|-----------|-------------|------------|
| Linear Search | O(1) | O(n) | O(n) |
| Binary Search | O(1) | O(log n) | O(log n) |

### Observation
Binary search performs much faster than linear search for large sorted arrays.

---

# Task 3: Recursion and Recurrence Validation

Implemented:

1. Factorial (Recursive)
2. Fibonacci (Naïve Recursive)
3. Fibonacci (Dynamic Programming)

### Observation

| Algorithm | Time Complexity |
|----------|----------------|
| Factorial | O(n) |
| Fibonacci Recursive | O(2ⁿ) |
| Fibonacci Dynamic Programming | O(n) |

Dynamic programming significantly reduces computation time.

---

# Task 4: Solving Recurrences through Code

Implemented recursive functions corresponding to:

1. T(n) = T(n/2) + n
2. T(n) = 2T(n/2) + n

### Expected Complexities

| Recurrence | Complexity |
|-------------|-----------|
| T(n) = T(n/2) + n | O(n) |
| T(n) = 2T(n/2) + n | O(n log n) |

---

# Technologies Used

- Python 3
- Matplotlib
- Random Library
- Time Library

---

# Project Structure
ADA-Lab-Assignment1
│
├── algorithms_assignment1.py
├── README.md
├── requirements.txt
└── plots/


---

# How to Run

Install dependencies:


pip install matplotlib


Run the program:

---

# Conclusion

This assignment demonstrates how algorithm performance varies depending on time complexity. Through experimentation and visualization, we observed how efficient algorithms scale better for larger inputs.
