### [22,27,16,2,18,6] -> Insertion Sort


1) Write the steps of the array given above by the sorting type.

    #### [22,27,16,2,18,6] Original 
    
    [2,27,16,22,18,6] -> Change 22 with 2.
    
    [2,6,16,22,18,27] -> Change 27 with 6.
    
    [2,6,16,22,18,27] -> *Look for a smaller amount to change with 16, if can't find it, stay the same*
    
    [2,6,16,18,22,27] -> Change 22 with 18.
    
    [2,6,16,18,22,27] -> *Look for a smaller amount to change with 22, if can't find it, stay the same.*
    
    [2,6,16,18,22,27] -> There is no other number to change with 27, stay the same.
    
2) Write the Big-O notation.

    O(n<sup>2</sup>)

3) Time Complexity:

    3.1) Average case: O(n<sup>2</sup>)

    3.2) Worst case: O(n<sup>2</sup>)

    3.3) Best case: O(n)

4) After sorting the array, write the case type of the number "18".

    Avarage case

5) Write the first 4 steps of the following array by Insertion Sort [7,3,5,8,2,9,4,15,6].

    #### [7,3,5,8,2,9,4,15,6] Original
    
    [2,3,5,8,7,9,4,15,6] -> Change 7 with 2
    
    [2,3,5,8,7,9,4,15,6] -> *Look for a smaller amount to change with 3, if can't find it, stay the same.*
    
    [2,3,4,8,7,9,5,15,6] -> Change 5 with 4
    
    [2,3,4,5,7,9,8,15,6] -> Change 8 with 5
    
    [2,3,4,5,6,9,8,15,7] -> Change 7 with 6
