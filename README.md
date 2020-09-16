# MERGE-SORT
Merge sort is a sorting technique based on divide and conquer technique. With worst-case time complexity being Ο(n log n), it is one of the most respected algorithms.

Merge sort first divides the array into equal halves and then combines them in a sorted manner.

# APPROACH
Step 1 − if it is only one element in the list it is already sorted, return.
#
Step 2 − divide the list recursively into two halves until it can no more be divided.
#
Step 3 − merge the smaller lists into new list in sorted order.

# COMPLEXITY
# TIME COMPLEXITY
# Worst Case Complexity [Big-O]: O(n2)
It occurs when the pivot element picked is either the greatest or the smallest element.
This condition leads to the case in which the pivot element lies in an extreme end of the sorted array. One sub-array is always empty and another sub-array contains n - 1 elements. Thus, quicksort is called only on this sub-array.
However, the quick sort algorithm has better performance for scattered pivots.

# Best Case Complexity [Big-omega]: O(n*log n)
It occurs when the pivot element is always the middle element or near to the middle element.
# Average Case Complexity [Big-theta]: O(n*log n)
It occurs when the above conditions do not occur.
# Space Complexity

The space complexity for quicksort is O(log n).

# Quicksort Applications
Quicksort is implemented when:-

The programming language is good for recursion
Time complexity matters
Space complexity matters


# REFERENCE
## 1.My code school(merge sort):- 

https://www.youtube.com/watch?v=TzeBrDU-JaY&t=328s

## 2.My code school(analyisis of merge sort):- 
https://www.youtube.com/watch?v=0nlPxaC2lTw
