# Largest-perfect-square-number-in-an-Array


Given an array of n integers. The task is to find the largest number which is a perfect square. Print -1 if there is no number that is perfect square.

Examples:

Input : arr[] = {16, 20, 25, 2, 3, 10} 
Output : 25
Explanation: 25 is the largest number 
that is a perfect square. 

Input : arr[] = {36, 64, 10, 16, 29, 25| 
Output : 64


A Simple Solution is to sort the elements and sort the n numbers and start checking from back for a perfect square number using sqrt() function. The first number from the end which is a perfect square number is our answer. The complexity of sorting is O(n log n) and of sqrt() function is log n, so at the worst case the complexity is O(n log n).

An Efficient Solution is to iterate for all the elements in O(n) and compare every time with the maximum element, and store the maximum of all perfect squares.
