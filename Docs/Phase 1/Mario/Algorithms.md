# Title

> Nov 4, 2020
> Sorting and binary search 

<p align="center">
  <img src="https://github.com/OutatimeSoftware/ProjectOne/blob/main/Img/binarySearch.jpg">
</p>

The concept of efficiency is often associated with algorithms.

Java offers a significant amount of ready to use sorting algorithms. Arrays can be sorted (into their natural order) using the class method sort of the Arrays-class. Lists can be sorted (into their natural order) using the class method sort of the Collections class.

Binary Search
When the data searched is in order, searching can be implemented a lot more efficiently than in linear search. The idea behind Binary Search is to start looking for the searched value in the middle index of the array (or list), compare the value found there to the searched value, and if needed (i.e, when the value isn't found there) eliminate half of the search area.

Steps:
-The array or list searched must be sorted
-The search begins in the middle of the array or list
-If the value in the middle-point being examined isn't the searched value, eliminate half of the searched area, and move on to examine the middle-point of the remaining half.
-If the value in the middle-point being examined is the searched value, return the index of the middle-point being examined.
-If there is nowhere left to search (the entire area has been eliminated), return the value -1, indicating that the searched value was not found (i.e, it wasn't in the list or array searched).