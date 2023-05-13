## Introduction: Sort Methododes

Introduction: Sorting Methododes

Imagine what it would be like to look up a number in a phone book if the names of the people were not listed in alphabetical order? It would be very complicated. The sorting or classification of records consists of arranging them in ascending or descending order and thus facilitating the retrieval of this data. The sorting has the objective of facilitating searches for occurrences of a certain element in an ordered set.

In computing there are a number of algorithms that use different sorting techniques to organize a data set, they are known as Sorting Methods or Sorting Algorithms. Let's learn a little more about them.

Sorting methods are classified into:

   - Internal Sorting: where all the elements to be sorted fit in the main memory and any record can be immediately accessed.

   - External Sorting: where the elements to be sorted do not fit in the main memory and the records are accessed sequentially or in large blocks.

Simple methods are suitable for small vectors, they are small programs and easy to understand. They have complexity C(n) = O(n²), that is, they require O(n²) comparisons. Examples: Insertion Sort, Selection Sort, Bubble Sort, Comb Sort.

## What is the Big O notation: complexity of time and space

To understand what the Big O notation is, let's take a look at a typical example, O(n²), which is usually also called "Big O quadratic". The letter "n" represents the size of the input, while the function "g(n) = n²" internal to "O()" gives us the idea of the complexity of the algorithm relative to the size of the input.

A typical algorithm that has complexity O(n²) would be the selection sort algorithm. The selection sort is a sorting algorithm that iterates through a list to ensure that each element at index i is the i-th smallest/biggest element in the list. (Selection Sort loops illustrated) https://www.freecodecamp.org/portuguese/news/content/images/2021/12/1_1ajbPJXjt3z7CofVODlaCw.png Here we have the formal definition of Big O: https://www.freecodecamp.org/portuguese/news/content/images/2021/12/0_cyqWw3UxODl-wqJi.jpg

## Brief explanation of the Algorithms:

   **[Insertion Sort]**

Insertion Sort is the method that runs through an array of elements from left to right and as it proceeds it sorts the elements to the left. It has complexity C(n) = O(n) in the best case and C(n) = O(n²) in the middle and worst case. It is considered a stable sorting method.

The operation of the algorithm is quite simple: it consists of each step from the second element selecting the next item in the sequence and placing it in the appropriate place according to the sorting criteria.
https://d2m498l008ebpa.cloudfront.net/2016/12/insertion-sort-animation-1-1.gif, in this gif we have how it works.

   **[Selection Sort]**

The selection sort consists of selecting the smallest item and placing it in the first position, select the second smallest item and place it in the second position, follow these steps until only one element remains. For all cases (best, average and worst case) it has complexity C(n) = O(n²) and is not a stable algorithm. https://d2m498l008ebpa.cloudfront.net/2016/12/selection-sort-animation-2-1.gif, picture of the sorting in operation.

   **[Quick Sort]**

The Quicksort Algorithm, created by C. A. R. Hoare in 1960, is the fastest known internal sorting method for a wide variety of situations.

It is probably the most widely used. It has complexity C(n) = O(n²) in the worst case and C(n) = O(n log n) in the best and middle case and is not a stable algorithm.

It is a comparison algorithm that employs the "divide and conquer" strategy. The basic idea is to divide the problem of sorting a set with n items into two smaller problems. The smaller problems are sorted independently and the results are combined to produce the final solution.

Basically the operation of the algorithm can be summarized in the following strategy: it divides its input list into two sub-lists from a pivot, and then performs the same procedure on the two smaller lists down to a unit list.

Operation of the algorithm: https://d2m498l008ebpa.cloudfront.net/2016/12/quicksort.gif

Pick an element from the list called the pivot.
Reorders the list so that the elements smaller than the pivot are on one side and the larger elements are on the other side. This operation is called "partitioning".
Recursively sorts the sublist below and above the pivot.

   **[Merge sort]**

Created in 1945 by American mathematician John Von Neumann the Mergesort is an example of a sorting algorithm that makes use of the "divide and conquer" strategy to solve problems. It is a stable method and has complexity C(n) = O(n log n) for all cases.

This algorithm splits the problem into smaller pieces, solves each piece and then merge the results together. The vector will be divided into two equal parts, which will each be divided into two parts, and so on until one or two elements remain whose ordering is trivial.

To merge the ordered parts the two elements of each part are separated and the smallest of them is selected and removed from its part. Then the smallest among the remaining ones are compared and so it proceeds until the parts are joined. Operation: https://d2m498l008ebpa.cloudfront.net/2016/12/merge-sorte-animation.gif

   **[Shell Sort]**

Created by Donald Shell in 1959, the Shell Sort method is an extension of the insertion sorting algorithm. It allows the exchange of records that are far apart from each other, unlike the insertion sorting algorithm which has the exchange of adjacent items to determine the insertion point. The complexity of the algorithm is unknown, nobody has yet been able to find a closed formula for its complexity function and the method is not stable.

The separated items of h positions (distant items) are sorted: the element at position x is compared and exchanged (if it satisfies the sort condition) with the element at position x-h. This process repeats until h=1, when this condition is satisfied the algorithm is equivalent to the insertion method.

The choice of jump h can be any sequence ending with h=1.

h(s) = 1, for s = 1
h(s) = 3h(s - 1) + 1, for s > 1
The sequence corresponds to 1, 4, 13, 40, 121, ...

Knuth (1973) showed experimentally that this sequence is hard to beat by more than 20% in efficiency.

   **[Bubble Sort]**

Probably the most famous sorting algorithm is bubble sorting. It is worth noting that there are thousands of mutations from it, and it is mainly used for educational purposes - as the first algorithm you learn.

So, what is the type of bubble? Imagine we are taking the first two elements. If the first element is larger than the second, we swap them. Now we take the second and third elements - we repeat. So in the end, the largest element will be the last member of the matrix. Now we repeat the operation for the first n-1 numbers, so n-2 and so on. Operation: https://lh5.googleusercontent.com/_oLwPF5ZvaZZ4pGD-HvSUSw6nTwwHjUwcLpNigUvb24-PKNwjMUwXcWYWf2wp4HopzHkh9JVmZd_AFYP4HjSYelidbw4FRo1fHrWV3KxbFM13xlRLALb-y-EbLhEmln11lhwEZPV


Referências: https://blog.betrybe.com/tecnologia/bubble-sort-tudo-sobre/ 
https://www.treinaweb.com.br/blog/conheca-os-principais-algoritmos-de-ordenacao
https://www.freecodecamp.org/portuguese/news/o-que-e-a-notacao-big-o-complexidade-de-tempo-e-de-espaco/
