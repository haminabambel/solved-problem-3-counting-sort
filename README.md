Download Link: https://assignmentchef.com/product/solved-problem-3-counting-sort
<br>
In general, the best performance you can hope to accomplish with sorting is an O(n log n) solution. When you know that the number of unique values you will be sorting is relatively small compared to the size of the list (n), you can improve on this solution by using a method called counting sort. The general premise of counting sort is as follows:

1. Iterate over the list one time and count the frequency of each value that occurs. This can be done in O(n) time.

2. Sort the list of unique values, which is much smaller than the size of the list, and therefore much faster to sort. This can be done in O(k log k) time, where k is the COMP 1005/1405 – S17 – A5 Due Tuesday, June 13 at 11:55 PM 3 number of unique values in the list. Since k is much less than n, this is much faster than O(n log n)

3. Generate a new, sorted list by iteratively adding the correct number of repetitions of each unique value in the correct order. This can be done in O(n) time. create a Python file called count.py and implement a function called countsort that takes a list as input. This function must return a new, sorted copy of the input list using the counting sort method described above. Note – for this question, you can use a built-in sorting function that Python offers to sort the unique values, or implement any other sorting algorithm if you want.