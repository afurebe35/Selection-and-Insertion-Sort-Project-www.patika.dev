# Selection-and-Insertion-Sort-Project-www.patika.dev
Selection and Insertion Sort Project

[22,27,16,2,18,6] -> Insertion Sort

After comparing the first 2 elements of the array, it is clear that 27 > 22 and this is a sorted sub-array.
[22,27,16,2,18,6]

Moving on to next element, 16 < 27. So, 16 and 27 elements should be swapped. Again, 16 < 22, and the elements should be swapped again.
[16,22,27,2,18,6]

Checking 2 < 27, 2 < 22, 2 < 16. 2 must be put before 16. 
[2,16,22,27,18,6]

Comparing 18 and 27. 18 < 27, 18 < 22, 18 > 16. So, 18 must be replaced and should be in between 16 and 22.
[2,16,18,22,27,6]

The last comparison is in between 27 and 6. Since, 6 < 27,22,16 but > 2 , indicates that it must be put in between 2 and 16. 
[2,6,16,18,22,27]

The final array that has been formed by using the insertion sort is:
[2,6,16,18,22,27]


To place the first element there has been "n" number of occurances.
Second element' s process took "n-1" occurances since the first element was clear.
The steps of this sorting will continue as it is described above.

The total occurances this process produced = n*(n+1)/2 = (n^2+n)/2
Big-o notation of this sorting =  O(n^2)

The complexity of this sorting could be expressed as an " average case" since the element of "18" is in the middle. 


[7,3,5,8,2,9,4,15,6] the first 4 steps of this array as it is sorted by selection sorting method:

[2,3,5,8,7,9,4,15,6]
Since 2 is the smallest element in the array it is swapped with 7.

[2,3,5,8,7,9,4,15,6]
The second smallest number is 3 and it is right after 2, there is no need to swap.

[2,3,4,8,7,9,5,15,6]
After finding the 4, 5 and 4 is swapped.

[2,3,4,5,7,9,8,15,6]
8 and 5 is swapped because 5 is the smallest number after 4.

The first 4 steps of the selection sort on this array is demonstrated above, the rest of the sorting continues as it was shown.
