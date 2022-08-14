# HeapSorterApp
A calculator UI based Heap Sorter

Heap Sort is one of the best sorting methods being in-place and with no quadratic worst-case running time. Heap sort involves building a Heap data structure from the given array and then utilizing the Heap to sort the array.

You must be wondering, how converting an array of numbers into a heap data structure will help in sorting the array.

What is a Heap ?

Heap is a special tree-based data structure, that satisfies the following special heap properties:
1.Shape Property: Heap data structure is always a Complete Binary Tree, which means all levels of the tree are fully filled.
2.Heap Property: All nodes are either greater than or equal to or less than or equal to each of its children. If the parent nodes are greater than their child nodes, heap is called a Max-Heap, and if the parent nodes are smaller than their child nodes, heap is called Min-Heap.


Heap sort algorithm is divided into two basic parts:

1.Creating a Heap of the unsorted list/array.
Then a sorted array is created by repeatedly removing the largest/smallest element from the heap, and inserting it into the array. The heap is reconstructed after each removal.

2.Initially on receiving an unsorted list, the first step in heap sort is to create a Heap data structure(Max-Heap or Min-Heap). Once heap is built, the first element of the Heap is either largest or smallest(depending upon Max-Heap or Min-Heap), so we put the first element of the heap in our array. Then we again make heap using the remaining elements, to again pick the first element of the heap and put it into the array. We keep on doing the same repeatedly untill we have the complete sorted list in our array.

In the utilized algorithm, initially heapsort() function is called, which calls heapify() to build the heap.

*Complexity Analysis of Heap Sort

Worst Case Time Complexity: O(n*log n)

Best Case Time Complexity: O(n*log n)

Average Time Complexity: O(n*log n)

Space Complexity : O(1)
