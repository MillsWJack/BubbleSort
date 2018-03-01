# BubbleSort
Implementation of a bubble sort sorting algorithm using a random number of elements and random values.

This algorithm works by stepping through the elements of a list and compares two neighboring elements to each other and swaps them if the current one is larger than the following element. This means that the larger values are sorted first and the smaller values "sink" to the bottom; explaining why this algorithm is also known as the sinking sort.

The algorithm itself uses a nested loop while comparing the elements, if we calculate the Big Oh notation it would look something like this:

![alt text](https://i.imgur.com/ajZ79Lz.png)

This shows the resulting Big O notation as O(n²) from the nested loops

Further reading:
https://en.wikipedia.org/wiki/Bubble_sort
https://en.wikipedia.org/wiki/Big_O_notation
