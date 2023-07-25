Sorting Algorithms Project

Background Context

This project is meant to be completed by groups of two students who will pair program for at least the mandatory part. 
The main goal is to learn about sorting algorithms, Big O notation, and how to select the best sorting algorithm for a given input.

Learning Objectives

We are able to explain the following concepts to anyone without the help of external resources:

At least four different sorting algorithms
What is the Big O notation and how to evaluate the time complexity of an algorithm
How to select the best sorting algorithm for a given input
What is a stable sorting algorithm

Requirements

Allowed editors: vi, vim, emacs
All files will be compiled on Ubuntu 20.04 LTS using gcc with the options -Wall -Werror -Wextra -pedantic -std=gnu89
All files should end with a new line
A README.md file at the root of the project folder is mandatory
Code should use the Betty style, which will be checked using betty-style.pl and betty-doc.pl
Not allowed to use global variables
No more than 5 functions per file
Unless specified otherwise, the standard library is forbidden (e.g., printf, puts, etc.)
Prototypes of all functions should be included in the header file called sort.h
All header files should be include guarded
Data Structure and Functions
For this project, students are given the following print_array and print_list functions:

void print_array(const int *array, size_t size);
void print_list(const listint_t *list);
The print_array.c and print_list.c files (containing the print_array and print_list functions) 
will be compiled with the students' functions during the correction.

Sorting Algorithms Tasks

The project consists of several tasks, each of which requires implementing a specific sorting algorithm and providing the Big 
O notation for its time complexity. The tasks include:

Bubble sort
Insertion sort
Selection sort
Quick sort
Each sorting algorithm should be implemented in separate C files and should be able to sort arrays of integers in ascending order. 
Additionally, the algorithms must be capable of printing the array after each time two elements are swapped during the sorting process.
