# Insertion-sort-in-C
This repository contains an implementation of the Insertion Sort algorithm in the C programming language. Insertion Sort is a simple and intuitive sorting algorithm that builds the final sorted array one item at a time. 
Algorithm Description
Insertion Sort works similarly to the way you might sort playing cards in your hands. The algorithm iterates through the list, growing the sorted portion of the list one element at a time. At each iteration, it removes one element from the input data, finds the location it belongs within the sorted list, and inserts it there. It continues until no elements remain in the input list.

Steps:
Start with the second element of the array (the first element is considered sorted).
Compare the current element with the largest value in the sorted array.
If the current element is smaller, compare it to the elements in the sorted array (from right to left) and shift all larger elements one position to the right.
Insert the current element into its correct position.
Repeat until the array is fully sorted.
Complexity
Time Complexity: O(n²) in the average and worst cases, and O(n) in the best case (when the array is already sorted).
Space Complexity: O(1), as it requires only a constant amount of additional space.
Implementation
The implementation provided in this repository is a standard version of the Insertion Sort algorithm in C. The code is well-commented and easy to understand, making it suitable for educational purposes or for use as a starting point in more complex projects.
