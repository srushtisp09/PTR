1.When the array is sorted, the first element is always unique by default because uniqueness is checked by comparing with a previous element, and index 0 has no previous element.
This same assumption shows up in:

Remove Duplicates II
Longest consecutive sequence
Many sliding window problems

2.Whenever the array is sorted and the code asks for finding the target we use search operation called binary operstion 
in problems like :Search insert position: we use binary search and at last when the target is not found we r supposed to return the index where it would be present in array .  
when target is not found, return start/left
because start always points to the first element 
GREATER than target = the insert position