# ArrayIndexOutOfBoundsException in Java

This repository demonstrates a common Java error: the `ArrayIndexOutOfBoundsException`.  The error occurs when trying to access an array element using an index that is outside the valid range of indices (0 to array.length - 1). The provided code example showcases this issue and provides a solution.

## Bug

The `bug.java` file contains a program that initializes an integer array and attempts to access an element beyond its bounds, resulting in an `ArrayIndexOutOfBoundsException`. 

## Solution

The `bugSolution.java` file corrects this by modifying the loop condition to ensure the index remains within the valid range of the array.