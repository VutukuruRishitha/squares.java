**README**

This program solves the problem of finding the squares of a sorted integer array and returning them in non-decreasing order. Although the input array is already sorted, squaring negative numbers can change the order. To handle this efficiently, the solution uses the **two-pointer technique**, comparing elements from the beginning and end of the array to determine the largest square at each step.

The algorithm runs in **O(n) time complexity**, making it more efficient than squaring all elements and then sorting. A new result array is filled from the end by placing the larger square from either pointer and moving inward. This approach is well-suited for coding interviews, competitive programming, and platforms like LeetCode, ensuring both correctness and optimal performance.
